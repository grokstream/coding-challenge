# Grok javascript coding-challenge

Sum all prime numbers from 0 to 10,000. Total operation time cannot exceed 2 minutes (assuming you're using a processor > 2.0 GHz)

Create a graph using any charting library you would like. For the x,y labels: x should be the prime number, y should be the cumlative sum of prime numbers including that number. For example:

x = [1,3,5,7,11] //the primes

y = [1,4,9,16,27] //the sums

So the payload for the graph would look something like [[1,1], [3,4], [5,9], [7,16]]

Each time the sum is calculated, plot it on the graph. In other words, when I click a button to begin this process, it SHOULD NOT show a white page until the end and then show a graph. The javascript should build the graph as it calculates, appending each sum at a time and UPDATING the graph. It should show the graph accumulating sums over time, not just present them at the end. 

# Put your app up on github. Be sure the app includes a script to make installing dependecies easy (if needed).

