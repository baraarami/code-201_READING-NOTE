# Images
Controlling the size and alignment of
your images using CSS keeps rules that
affect the presentation of your page in
the CSS and out of the HTML markup.

You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.
Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.
You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages.


First you need to determine the
sizes of images that will be used
commonly throughout the site,
then give each size a name.
For example:
small
medium
large
Where the <img> elements
appear in the HTML, rather
than using width and height
attributes you can use these
names as values for the class
attribute.
In the CSS, you add selectors for
each of the class names, then
use the CSS width and height
properties to control the image
dimensions
![image](https://user-images.githubusercontent.com/79080942/111040672-ce5c6d00-843c-11eb-9ed6-ee885b86a824.png)


In the last chapter, you saw how
the float property can be used
to move an element to the left or
the right of its containing block,
allowing text to flow around it.
Rather than using the <img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:
1: The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).
2: New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

![image](https://user-images.githubusercontent.com/79080942/111040728-1b404380-843d-11eb-9508-af4f54356455.png)

By default, images are inline
elements. This means that they
flow within the surrounding text.
In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.
Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:
1: On the containing element,
you can use the text-align
property with a value of center.
2: On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.
You can specify class names
that allow any element to be
centered, in the same way that
you can for the dimensions or
alignment of images.

![image](https://user-images.githubusercontent.com/79080942/111040737-301cd700-843d-11eb-97cc-5906ac2be1ce.png)

The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.

The background-repeat
property can have four values:
repeat
The background image is
repeated both horizontally and
vertically (the default way it
is shown if the backgroundrepeat
property isn't used).
repeat-x
The image is repeated
horizontally only (as shown in
the first example on the left).
repeat-y
The image is repeated vertically
only.
no-repeat
The image is only shown once.
The background-attachment
property specifies whether a
background image should stay in
one position or move as the user
scrolls up and down the page. It
can have one of two values:
fixed
The background image stays in
the same position on the page.
scroll
The background image moves
up and down as the user scrolls
up and down the page.

When an image is not being
repeated, you can use the
background-position
property to specify where in the
browser window the background
image should be placed.
This property usually has a pair
of values. The first represents
the horizontal position and the
second represents the vertical.
** left top
** left center
** left bottom
** center top
** center center
** center bottom
** right top
** right center
** right bottom
If you only specify one value,
the second value will default to
center.

The background property acts
like a shorthand for all of the
other background properties
you have just seen, and also the
background-color property.
The properties must be specified
in the following order, but you
can miss any value if you do not
want to specify it.
1: background-color
2: background-image
3: background-repeat
4: background-attachment
5: background-position
CSS3 will also support the use
of multiple background images
by repeating the background
shorthand. Because few
browsers supported this
property at the time of writing, it
was not commonly used.
div {
background:
url(example-1.jpg)
top left no-repeat,
url(example-2.jpg)
bottom left no-repeat,
url(example-3.jpg)
centre top repeat-x;}
The first image is shown on top,
with the last one on the bottom.

If you want to overlay text on a background image, the image must be low
contrast in order for the text to be legible.
Contrast of
background images
1- High Contrast 
2- Low Contrast 
3- Screen




# Practical  Information
To wrap up the book we are going to look
at some practical information that will
help you launch a successful site.

In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability.
On-Page SEO
1: Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the <title> element which lives
inside the <head> element.
2: URL / Web Address
The name of the file is part of
the URL. Where possible, use
keywords in the file name.
3: Headings
If the keywords are in a heading
<hn> element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.
4: Text
Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.
5: Link Text
Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").
6: Image Alt Text
Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.
7: Page Descriptions
The description also lives inside
the <head> element and is
specified using a <meta> tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)
Never try to fool search engines!
They will penalize you for it. For
example, never add text in the
same color as the background of
the page as they can detect this.

![image](https://user-images.githubusercontent.com/79080942/111040896-29db2a80-843e-11eb-8e87-f3800cae38e1.png)


## How to Identify Keywords and Phrases
Determining which keywords to use on your site can be one of the
hardest tasks when you start to think about SEO. Here are six steps that
will help you identify the right keywords and phrases for your site.


## Learning about your Visitors
As soon as people start coming to your site, you can start analyzing
how they found it, what they were looking at and at what point they are
leaving. One of the best tools for doing this is a free service offered by
Google called Google Analytics.

## How Many People Are Coming to Your Site?
The overview page gives you a snapshot of the key information you are
likely to want to know. In particular, it tells you how many people are
coming to your site

## What Are Your Visitors Looking At?
The content link on the left-hand side allows
you to learn more about what the visitors are
looking at when they come to your site.

## Where Are Your Visitors Coming From?
The traffic sources link on the left hand side
allows you to learn where your visitors are
coming from.

Many companies provide platforms for blogging, email
newsletters, e-commerce and other popular website
tools (to save you writing them from scratch).






