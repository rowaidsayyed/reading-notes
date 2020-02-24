# Welcome 201d3

## Layout
CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.
* Block-level boxes start on a new line and act as the main building blocks of any layout.
* inline boxes flow between surrounding text.

### position
CSS has the positioning schemes that allow us to control the layout of a page: 
* normal flow
* relative positioning
* absolute positioning

### z-index
When we use relative, fixed, or absolute positioning, boxes can overlap. to control which element sits on top, we can use
the **z-index** property.

### float
The float property allows us to take an element in normal flow and place it as far to the left or right of the containing
element as possible.
When we use the float property, we should also use the **width property** to indicate how wide the floated element should
be.

#### Clearing Floats
The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. 

## Fixed width and Fluid width 
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window.
* Measurements tend to be given in pixels.
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. 
* Measurments tend to use percentages.

## Layout Grids
Grids set consistent proportions and spaces between items which helps to create a professional looking design.
Possible Layouts:
* 960 Pixel wide -- 12 Column Grid

## CSS Frameworks
CSS frameworks aim to make our life easier by providing the code for common tasks so we can include the CSS
framework code in our projects rather than writing the CSS from scratch

### 960.GS CSS Framework
One of the most popular uses of CSS frameworks is in creating grids to layout pages.
