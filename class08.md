

  # LAYOUT

## Key Concepts in Positioning Elements

**Building Blocks**
CSS treats each HTML *element* as if it is in its
own *box*. This box will either be a __block-level
box or an inline box__.


### Block-level boxes (elements)
start on a new line and act as the main building blocks
of any layout `<h1>`  `<p> ` `<ul> ` `<li>`



### inline boxes (elements)
__flow between surrounding text__. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). `<img>`  `<b>`  `<i>`




**KEEP IN MINED**: *. To separate boxes, you can use
borders, margins, padding, and background colors. *


### Containing Elements
It is common to group a number of elements together inside a `<div>`
(or other block-level) element. 



### Controlling the Position of Elements
CSS has the following *positioning schemes* that allow you to control
the layout of a page: *normal flow, relative positioning, and absolute
positioning.* 
You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.


# 1. Normal flow

    Is to sit emlemnts side by side instead of apearing lower down each other
    
# 2. Relative Positioning


    This moves an element from the
    position it would be in normal
    flow, shifting it to the top, right,
    bottom, or left of where it
    would have been placed. This
    does not affect the position of
    surrounding elements; they stay
    in the position they would be in
    in normal flow    

        
# 3. Absolute positioning

    This positions the element
    in relation to its containing
    element. It is taken out of
    normal flow, meaning that it
    does not affect the position
    of any surrounding elements
    (as they simply ignore the
    space it would have taken up).
    Absolutely positioned elements
    move as users scroll up and
    down the page.    


To indicate where a box should be positioned, you may also need to use
**box offset** properties to tell the browser how far from the top or bottom
and left or right it should be placed. 


# - Fixed Positioning

    This is a form of absolute
    positioning that positions
    the element in relation to the
    browser window, as opposed
    to the containing element.
    Elements with fixed positioning
    do not affect the position of
    surrounding elements and they
    do not move when the user
    scrolls up or down the page.
    
# - Floating Elements

    Floating an element allows
    you to take that element out
    of normal flow and position
    it to the far left or right of a
    containing box. The floated
    element becomes a block-level
    element around which other
    content can flow
    
    
    
   *When you move
any element from
normal flow, boxes
can overlap. The
**z-index** property
allows you to control
which box appears
on top.*



## Creating Multi-Column Layouts with Floats


Many web pages use multiple
columns in their design. This
is achieved by using a `<div>`
element to represent each
column. The following three CSS
properties are used to position
the columns next to each other: **(width, float, margin)


 

