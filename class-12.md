# The HTML <canvas> element 
**is used to draw graphics on a web page.**

* The HTML \<canvas> element is used to draw graphics, on the fly, via JavaScript.

* The \<canvas> element is only a container for graphics. You must use JavaScript to actually draw the graphics.

* Canvas has several methods for drawing paths, boxes, circles, text, and adding images.
* Note: Always specify an id attribute (to be referred to in a script), and a width and height attribute to define the size of the canvas. To add a border, use the style attribute.

## Geid
Grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed.

There are three functions that draw rectangles on the canvas:

        fillRect(x, y, width, height)
        Draws a filled rectangle.
        strokeRect(x, y, width, height)
        Draws a rectangular outline.
        clearRect(x, y, width, height)
        Clears the specified rectangular area, making  it fully transparent.


 **x** and **y** specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle. width and height provide the rectangle's size.


 The **fillRect()** function draws a large black square 100 pixels on each side.

  **The clearRect()** function then erases a 60x60 pixel square from the center. 
  **strokeRect()** is called to create a rectangular outline 50x50 pixels within the cleared square.

## Drawing paths
**beginPath()**
Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.

**Path methods**
Methods to set different paths for objects.

**closePath()**
Adds a straight line to the path, going to the start of the current sub-path.

**stroke()**
Draws the shape by stroking its outline.

**fill()**
Draws a solid shape by filling the path's content area.


## Rectangles
In addition to the three methods we saw in Drawing rectangles, which draw rectangular shapes directly to the canvas, there's also the rect() method, which adds a rectangular path to a currently open path.

**rect(x, y, width, height)**
Draws a rectangle whose top-left corner is specified by (x, y) with the specified width and height.

Before this method is executed, the **moveTo()** method is automatically called with the parameters (x,y).

## Colors
             fillStyle = color
             Sets the style used when filling shapes.

            strokeStyle = color
            Sets the style for shapes' outlines.


 uses the **strokeStyle** property to change the colors of the shapes' outlines. We use the **arc() method** to draw circles instead of squares.
 
 ## Styling text
 
**font = value**
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. *The default font is 10px sans-serif.*

**textAlign = value**
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

**textBaseline = value**
Baseline alignment setting. Possible values: *top, hanging, middle, alphabetic, ideographic, bottom.* The default value is alphabetic.

**direction = value**
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.