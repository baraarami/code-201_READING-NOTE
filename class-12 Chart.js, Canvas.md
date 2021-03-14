# Chart.js, Canvas

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.
A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

Setting up
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script:
![11](https://user-images.githubusercontent.com/79080942/111068087-f47f1d00-84cf-11eb-9104-d382a978aaf7.PNG)

Drawing a line chart
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart
Next, we need to write a script that will retrieve the context of the canvas,
nside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart
If you test your file in a browser you’ll now see a cool animated line graph.

Drawing a pie chart
Our line chart is complete, so let’s move on to our pie chart.
Next, we need to get the context and to instantiate the chart
You’ll notice that this time, we are going to supply some options to the chart.

Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler 
Now, immediately after the pieData we’ll add our options
These options do two things, first they remove the stroke from the segments, and then they animate the scale of the pie so that it zooms out from nothing.

Drawing a bar chart
Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. 
Next, we retrieve the element and create the graph
And finally, we add in the bar chart’s data As you can see, the data is largely the same, except this time we’ve chosen to use RGBA to specify our colors which allows us to add transparency.
