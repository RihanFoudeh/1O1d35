# Docs for the HTML < canvas> Element & Chart.js Summary

## Charts : <br>

- Charts are far better for displaying data visually. <br>


### Chart Steps : <br>

- First thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.
- Write a script that will retrieve the context of the canvas.
- Inside the same script tags, we need to create our data, an object that contains labels for the base of our chart and datasets to describe the values on the chart.
- Move to the pie chart and write canvas element.
- Next, we need to create the data. supply a value and a color for each section.
- After the pieData we’ll add our options.
- Finally, let’s add a bar chart to our page by adding the canvas element.
- Next, we retrieve the element and create the graph.
- And finally, we add in the bar chart’s data
---------------------------------------------------------------------------------------------------------------------------------------------------------- <br>

### Basic usage of canvas: <br>

#### Canvas element: <br>
- It looks like the < img> element except it doesn’t have src and alt.
- It is similar to img with ( margin / border / background..  ) but different with (< video>, < audio>, or < picture> elements).
- It has only height and width. When you don’t add height and width, it will take 300 pixels wide and 150 pixels high.
- It requires the closing tag (</ canvas>).Drawing shapes with canvas:
- We will be using a canvas grid or coordinate space.
- It only supports two primitive shapes: rectangles and paths.
- other shapes must be created by combining one or more paths.fillRect(x, y, width, height).

 #### Draws a filled rectangle. <br>

- strokeRect(x, y, width, height)
- Draws a rectangular outline.
- clearRect(x, y, width, height)
- Clears the specified rectangular area, making it fully transparent.

#### Drawing paths: <br>

- First, you create the path.
-  Then you use drawing commands to draw into the path.
-  Once the path has been created, you can stroke or fill the path to render it.

#### Functions for drawing paths : <br>

- beginPath() / Creates a new path.
- Path methods / Methods to set different paths for objects.
- closePath() / Adds a straight line to the path, going to the start of the current sub-path.
- stroke() / Draws the shape by stroking its outline.
- fill() / Draws a solid shape by filling the path's content area.

#### Applying styles and colors : <br>

- use: fillStyle and stroke style.
- fillStyle = color
- Sets the style used when filling shapes.
- stroke style = color
- Sets the style for shapes' outlines.globalAlpha = transparency value
- Applies the specified transparency value to all future shapes drawn on the canvas.

#### Line styles: <br>
- lineWidth = value
- Sets the width of lines drawn in the future.
- lineCap = type
- Sets the appearance of the ends of lines.
- lineJoin = type
- Sets the appearance of the "corners" where lines meet.
- miter limit = value
- Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
- getLineDash()
- Returns the current line dash pattern array containing an even number of non-negative numbers.
- setLineDash(segments)
- Sets the current line dash pattern.
- lineDashOffset = value
- Specifies where to start a dash array on a line.

#### Drawing text: <br>
- fillText(text, x, y [, maxWidth])
- Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth])
- Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

#### Styling text: <br>
- font = value
- The current text style is used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
- textAlign = value
- Text alignment setting. Possible values: start, end, left, right, or center. The default value is started.
- textBaseline = value
- Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
- direction = value
- Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.
