
# Forms

Traditionally, the term 'form' has referred
to a printed document that contains
spaces for you to fill in information.
HTML borrows the concept of a form to refer to different
elements that allow you to collect information from visitors to
your site.



# Why Forms?
The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage

![image](https://user-images.githubusercontent.com/79080942/110518269-94c1f400-8114-11eb-81f4-551a30788cae.png)


There are several types of form controls that
you can use to collect information from visitors
to your site.

A form may have several form controls, each
gathering different information. The server
needs to know which piece of inputted data
corresponds with which form element.


# Form Structure
(form)
Form controls live inside a
<form> element. This element
should always carry the action
attribute and will usually have a
method and id attribute too.
action
Every <form> element requires
an action attribute. Its value
is the URL for the page on the
server that will receive the
information in the form when it
is submitted.
method
Forms can be sent using one of
two methods: get or post.
With the get method, the values
from the form are added to
the end of the URL specified in
the action attribute. The get
method is ideal for:
●● short forms (such as search
boxes)
●● when you are just retrieving
data from the web server
(not sending information that
should be added to or deleted
from a database)
  
  
  The <input> element is used
to create several different form
controls. The value of the type
attribute determines what kind
of input they will be creating.
type="text"
When the type attribute has a
value of text, it creates a singleline
text input.
name
When users enter information
into a form, the server needs to
know which form control each
piece of data was entered into.
(For example, in a login form, the
server needs to know what has
been entered as the username
and what has been given as the
password.) Therefore, each form
control requires a name attribute.
The value of this attribute
identifies the form control and is
sent along with the information
they enter to the server.
maxlength
You can use the maxlength
attribute to limit the number
of characters a user may enter
into the text field. Its value is the
number of characters they may
enter.

<input>
type="radio"
Radio buttons allow users to pick
just one of a number of options.
name
The name attribute is sent to
the server with the value of the
option the user selects. When
a question provides users with
options for answers in the form
of radio buttons, the value of
the name attribute should be the
same for all of the radio buttons
used to answer that question.
value
The value attribute indicates
the value that is sent to the
server for the selected option.
The value of each of the buttons
in a group should be different
(so that the server knows which
option the user has selected).
checked
The checked attribute can be
used to indicate which value (if
any) should be selected when
the page loads. The value of this
attribute is checked. Only one
radio button in a group should
use this attribute.



<select>
size
You can turn a drop down select
box into a box that shows more
than one option by adding the
size attribute. Its value should
be the number of options you
want to show at once. In the
example you can see that three
of the four options are shown.
Unfortunately, the way that
browsers have implemented this
attribute is not perfect, and it
should be tested throroughly if
used (in particular in Firefox and
Safari on a Mac).
multiple
You can allow users to select
multiple options from this list by
adding the multiple attribute
with a value of multiple.
  
  <input>
type="image"
If you want to use an image for
the submit button, you can give
the type attribute a value of
image. The src, width, height,
and alt attributes work just
like they do when used with the
<img> element



** Whenever you want to c XX ollect information from
visitors you will need a form, which lives inside a
<form> element.
  
** Information from a form is sent in name/value pairs.


** Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.


** HTML5 introduces new form elements which make it
easier for visitors to fill in forms.



There are several CSS properties that
were created to work with specific types
of HTML elements, such as lists, tables,
and forms.



The list-style-type property
allows you to control the shape
or style of a bullet point (also
known as a marker).
It can be used on rules that
apply to the <ol>, <ul>, and <li>
elements.
Unordered Lists
For an unordered list you can use
the following values:
none
disc
circle
square
Ordered Lists
For an ordered (numbered) list
you can use the following values:
decimal
1 2 3
decimal-leading-zero
01 02 03
lower-alpha
a b c
upper-alpha
A B C
lower-roman
i. ii. iii.
upper-roman

  
outside
The marker sits to the left of the
block of text. (This is the default
behaviour if this property is not
used.)
inside
The marker sits inside the box of
text (which is indented).
In the example shown, the width
of the list has been limited to 150
pixels. This ensures that the text
wraps onto a new line so you can
see how the value of inside sits
the bullet inside the first line of
text.

# Table Properties
width to set the width of the
table
padding to set the space
between the border of each table
cell and its content
text-transform to convert the
content of the table headers to
uppercase
letter-spacing, font-size
to add additional styling to the
content of the table headers
border-top, border-bottom
to set borders above and below
the table headers
text-align to align the writing
to the left of some table cells and
to the right of the others
background-color to change
the background color of the
alternating table rows
:hover to highlight a table row
when a user's mouse goes over it

Give cell s padding
If the text in a table cell either
touches a border (or another
cell), it becomes much harder to
read. Adding padding helps to
improve readability.
Distinguish headings
Putting all table headings in
bold (the default style for the
<th> element) makes them
easier to read. You can also
make headings uppercase and
then either add a background
color or an underline to clearly
distinguish them from content.
Shade alternate rows
Shading every other row can
help users follow along the lines.
Use a subtle distinction from the
normal color of the rows to keep
the table looking clean.
Al ign numerals
You can use the text-align
property to align the content
of any column that contains
numbers to the right, so that
large numbers are clearly
distinguished from smaller ones.
  
  show
This shows the borders of any
empty cells.
hide
This hides the borders of any
empty cells.
inherit
If you have one table nested
inside another, the inherit
value instructs the table cells to
obey the table.

font-size sets the size of the
text entered by the user.
color sets the text color, and
background-color sets the
background color of the input.
border adds a border around
the edge of the input box, and
border-radius can be used
to create rounded corners (for
browsers that support this
property).
The :focus pseudo-class is
used to change the background
color of the text input when it
is being used, and the :hover
psuedo-class applies the same
styles when the user hovers over
them.
background-image adds a
background image to the box.
Because there is a different
image for each input, we are
using an attribute selector
looking for the value of the id
attribute on each input.

color is used to change the
color of the text on the button.
text-shadow can give a 3D
look to the text in browsers that
support this property.
border-bottom has been used
to make the bottom border of
the button slightly thicker, which
gives it a more 3D feel.
background-color can make
the submit button stand out
from other items around it.
(Creating a consistent style
for all buttons helps users
understand how they should
interact with the site.) A gradient
background has been added for
browsers that support gradients.
Gradients are covered on
page 419.
The :hover pseudo-class
has been used to change the
appearance of the button when
the user hovers over it. In this
case, the background changes,
the text gets darker, and the
thicker border is applied to the
top of the button.

Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.

  
 Forms benefit from styles that make them feel more
interactive. 


# Event
When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events.

![image](https://user-images.githubusercontent.com/79080942/110519719-53324880-8116-11eb-845b-94ae5650cf45.png)
![image](https://user-images.githubusercontent.com/79080942/110519816-6c3af980-8116-11eb-87f1-68b6528f7c90.png)



Because you cannot have parentheses after the
function names in event handlers or listeners,
passing arguments requires a workaround.

![image](https://user-images.githubusercontent.com/79080942/110519990-9bea0180-8116-11eb-8a94-6fa22fad453a.png)



** Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).

** Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.

** When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.

** You can use event delegation to monitor for events
that happen on all of the children of an element.

** The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.

  
  
  
  
