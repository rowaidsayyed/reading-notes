# Welcome 201d3

## Charts 
Charts are far better for displaying data visually than tables

## Chart.js
It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

## canvas
At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes.
`<canvas>` element has only two attributes
* width
* height

* always a good idea to supply an id because this makes it much easier to identify it in a script.
The `<canvas>` element can be styled just like **any normal image**

The canvas is **initially blank**. To display something, a script first needs to access the rendering context and draw on it.

## Script file

The first line in the script retrieves the node in the DOM representing the `<canvas>` element by calling the **document.getElementById()** method. 

We can access the drawing context using its **getContext()**

`fillRect(x, y, width, height)` == Draws a filled rectangle.
`strokeRect(x, y, width, height)` == Draws a rectangular outline.
`clearRect(x, y, width, height)` == Clears the specified rectangular area, making it fully transparent.

### Draw paths
beginPath()
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
Path methods
Methods to set different paths for objects.
closePath()
Adds a straight line to the path, going to the start of the current sub-path.
stroke()
Draws the shape by stroking its outline.
fill()
Draws a solid shape by filling the path's content area.

### Colors
If we want to apply colors to a shape, there are two important properties we can use: 
1. fillStyle
2. strokeStyle

### Texts
The canvas rendering context provides two methods to render text:

1. `fillText(text, x, y [, maxWidth])`
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
2. `strokeText(text, x, y [, maxWidth])`
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.