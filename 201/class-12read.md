> # EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS


Charts are far better for displaying data visually than tables, They’re easier to look at and convey data quickly, but they’re not always easy to create.

It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.

Canvas looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes, the `<canvas>` element has only two attributes, width and height.

The id attribute isn't specific to the `<canvas>` element but is one of the global HTML attributes which can be applied to any HTML element (like class for instance).

The `<canvas>` element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas.

Drawing a line chart

To draw a line chart use this line to create a canvas element in our HTML `<canvas id="buyers" width="600" height="400"></canvas>`






> # Colors

Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

fillStyle = color

Sets the style used when filling shapes.

strokeStyle = color

Sets the style for shapes' outlines.