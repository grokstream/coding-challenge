# coding-challenge

Create a small 1 page app using Backbone or Angular. At the top of the page there should be an input field that takes a url. When you insert url and hit a "Draw" button the app should use ajax to query the given url [https://raw.githubusercontent.com/kyle-sorensen/coding-challenge/master/response.json](https://raw.githubusercontent.com/kyle-sorensen/coding-challenge/master/response.json) (there will other similar urls, use this one as a test, the payload structure will always be the same)

The url will give a json response of data which can be used as a payload and input into an interactive chart using the [D3 charting](https://d3js.org/) library.
By 'interactive' we mean you should be able to zoom the chart and look left to right. (Use d3-brush and d3-zoom for this feature.)

TLDR; Make a website with an input, which takes a url. The url will respond with json, use the json to build a chart. Use the D3 library with d3-brush and d3-zoom.

Put your app up on github. Be sure to make a script so we can install dependencies.
