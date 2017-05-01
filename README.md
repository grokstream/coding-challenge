# coding-challenge

Create a small 1 page app using Backbone or Angular. At the top of the page there should be an input field that takes a url. When you insert the url and hit a "Draw" button the app should use ajax to query the given url [https://raw.githubusercontent.com/kyle-sorensen/coding-challenge/master/response.json](https://raw.githubusercontent.com/kyle-sorensen/coding-challenge/master/response.json) (there will other similar urls, use this one as a test, the payload structure will always be the same)

The url will give a json response of data which can be used as a payload and input into an interactive chart using the [D3 charting](https://d3js.org/) library. The chart should use d3-zoom and d3-brush to make it more interactive. (You can zoom in on a date or stretch it. As long as it's using d3-zoom and d3-brush correctly you are fine. 

Put your app up on github. Be sure to make a script so we can install dependencies.
