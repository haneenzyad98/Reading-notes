
# Chart.js 

you can displaying data in many way like tables but the better choice for displaying data is chart.

it is help the reader to quick understand what the data means and it is good for the ceo to take a quick look for company conditions .

to creat chart the first thing need to download Chart.js folder then import the script in to html file 

<.script src='Chart.min.js'></script.>

to Drawing a line chart

need to create a canvas element in our HTML in which Chart.js can draw our chart. 

<.canvas id="buyers" width="600" height="400"></.canvas>

hat will retrieve the context of the canvas

Inside  script tags we  create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

then Drawing a pie chart

Finally Drawing a bar chart


## Basic usage of canvas

canvas has two attributes, width and height

The <canvas.> element can be styled just like any normal image (margin, border, background)

## Drawing shapes with canvas

supports two primitive shapes: rectangles and paths 

fillRect(x, y, width, height)

Draws a filled rectangle.


strokeRect(x, y, width, height)

Draws a rectangular outline.


clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.

and another  many shape you can do

## Applying styles and colors

fillStyle = color Sets the style used when filling shapes.

strokeStyle = color Sets the style for shapes' outlines.

we can draw  rectangles by for loops


## Drawing text

to render text

- fillText(text, x, y [, maxWidth])

Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

- strokeText(text, x, y [, maxWidth])

Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.