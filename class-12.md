# Charts.js
**Creating a Chart**
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.
To create a chart, we need to instantiate the Chart class. To do this, we need to pass in the node, jQuery instance, or 2d context of the canvas of where we want to draw the chart.

**Responsive Charts**
When it comes to changing the chart size based on the window size, a major limitation is that the canvas render size (canvas.width and .height) can not be expressed with relative values, contrary to the display size (canvas.style.width and .height).

**Interaction Modes**
When configuring interaction with the graph via hover or tooltips, a number of different modes are available:
1. point.
2. nearest.
3. single.
4. label.
5. index.
6. x axis.
7. database.
8. x
9. y.


# EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS
**Setting up**
The first thing we need to do is download Chart.js. Then create a new html page and import the script.

**Drawing a line chart**
To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. Next, we need to write a script that will retrieve the context of the canvas.Inside the same script tags we need to create our data.

**Drawing a pie chart**
First, we need the canvas element:
`<canvas id="countries" width="600" height="400"></canvas>`
Next, we need to get the context and to instantiate the chart. Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section.

**Drawing a bar chart**
First, we add the canvas element:
`<canvas id="income" width="600" height="400"></canvas>`
Next, we retrieve the element and create the graph. And finally, we add in the bar chart’s data.



# Basic usage of canvas
**The `<canvas>` element**
Indeed, the `<canvas>` element has only two attributes, width and height. These are both optional and can also be set using DOM properties.

the `<canvas>` element requires the closing tag (`</canvas>`). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.


# Drawing shapes with canvas
**The grid**
canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin.

**Drawing rectangles**
There are three functions that draw rectangles on the canvas:
1. fillRect(x, y, width, height): Draws a filled rectangle.
2. strokeRect(x, y, width, height): Draws a rectangular outline.
3. clearRect(x, y, width, height): Clears the specified rectangular area, making it fully transparent.

**Drawing paths**
Here are the functions used to draw a path:

1. beginPath(): Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
2. Path methods: Methods to set different paths for objects.
3. closePath(): Adds a straight line to the path, going to the start of the current sub-path.
4. stroke(): Draws the shape by stroking its outline.
5. fill(): Draws a solid shape by filling the path's content area.


# Applying styles and colors
**Colors**
If we want to apply colors to a shape, there are two important properties we can use: 

1. fillStyle = color: Sets the style used when filling shapes.
2. strokeStyle = color: Sets the style for shapes' outlines.

**Transparency**
This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

**Line styles**
There are several properties which allow us to style lines.

1. lineWidth = value: Sets the width of lines drawn in the future.
2. lineCap = type: Sets the appearance of the ends of lines.
3. lineJoin = type: Sets the appearance of the "corners" where lines meet.
4. miterLimit = value: Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
5. getLineDash(): Returns the current line dash pattern array containing an even number of non-negative numbers.
6. setLineDash(segments): Sets the current line dash pattern.
7. lineDashOffset = value: Specifies where to start a dash array on a line.


# Drawing text
**Drawing text**
The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth]): Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
2. strokeText(text, x, y [, maxWidth]): Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

**Styling text**
There are some more properties which let you adjust the way the text gets displayed on the canvas:

1. font = value.
2. textAlign = value.
3. textBaseline = value.
4. direction = value.

**Advanced text measurements**
In the case you need to obtain more details about the text, the following method allows you to measure it.

- measureText(): 
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.
