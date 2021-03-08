# We willlook at how to control where each element sits on a page and how to create attractive page layouts.
This involves learning about how designing for a screen can be
different to designing for other mediums (such as print).


Building Blocks
CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.
Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors.


# Controlling the Position of Elements

CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.


### Normal flow
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside,
they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else).


### Relative Positioning
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.


### Absolute positioning
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



## position:static
In normal flow, each block-level
element sits on top of the next
one. Since this is the default
way in which browsers treat
HTML elements, you do not
need a CSS property to indicate
that elements should appear
in normal flow, but the syntax
would be:
position: static;


## position:relative
Relative positioning moves an
element in relation to where it
would have been in normal flow.


## position:absolute
When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.)
The box offset

## position:fixed 
Fixed positioning is a type
of absolute positioning that
requires the position property
to have a value of fixed.
It positions the element in
relation to the browser window.
Therefore, when a user scrolls
down the page, it stays in the
exact same place. It is a good
idea to try this example in your
browser to see the effect.

## float
The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.
Anything else that sits inside
the containing element will
flow around the element that is
floated.

## clear
left
The left-hand side of the box
should not touch any other
elements appearing in the same
containing element.
right
The right-hand side of the
box will not touch elements
appearing in the same containing
element.
both
Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.
none
Elements can touch either side.


## CREATING Multi-Column Layouts with Floats
Many web pages use multiple
columns in their design. This
is achieved by using a <div>
element to represent each
column. The following three CSS
properties are used to position
the columns next to each other:
width
This sets the width of the
columns.
float
This positions the columns next
to each other.
margin
This creates a gap between the
columns.



### A FIXED WIDTH LAYOUT
To create a fixed width layout,
the width of the main boxes on
a page will usually be specified
in pixels (and sometimes their
height, too).
Here you can see several <div>
elements, each of which uses an
id or class attribute to indicate
its purpose on the page.
In a book like this, the result of
both the fixed and liquid layouts
look similar. To get a real feel for
them, you need to view them in
your browser and see how they
react when you adjust the size of
the browser window.
The fixed width layout will stay
the same width no matter what
size the browser window is,
whereas the liquid layout will
stretch (or shrink) to fill the
screen.
The HTML is the same for both
the fixed width layout example
on this page and the liquid layout
example you see next.
A Fixed Width Layout


### A LIQUID LAYOUT
The liquid layout uses
percentages to specify the width
of each box so that the design
will stretch to fit the size of the
screen.


### Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).


### Grids help create professional and flexible designs.
### CSS Frameworks provide rules for common tasks.
### You can include multiple CSS files in one page.



