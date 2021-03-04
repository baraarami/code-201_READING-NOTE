# IMAGE 
There are many reasons why you might
want to add an image to a web page: you
might want to include a logo, photograph,
illustration, diagram, or chart.



Choosing Images for Your Site
A picture can say a thousand words, and great
images help make the difference between an
average-looking site and a really engaging one.

Images can be used to set the
tone for a site in less time than
it takes to read a description. If
you do not have photographs
to use on your website, there
are companies who sell stock
images; these are images you
pay to use (there is a list of stock
photography websites below).
Remember that all images are
subject to copyright, and you
can get in trouble for simply
taking photographs from
another website.
If you have a page that shows
several images (such as product
photographs or members of a
team) then putting them on a
simple, consistent background
helps them look better as
a group .



# Images should...
* Be relevant
* Convey information
* Convey the right mood
* Be instantly recognisable
* Fit the color palette


Storing Images on Your Site
If you are building a site from scratch, it is good
practice to create a folder for all of the images
the site uses.
As a website grows, keeping
images in a separate folder
helps you understand how the
site is organized. Here you can
see an example of the files for
a website; all of the images are
stored in a folder called images.




# Adding Images:

To add an image into the page
you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
(src):
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
(alt)
This provides a text description
of the image which describes the
image if you cannot see it.
(title)
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.


# Height & Width of Images
You will also often see an <img>
element use two other attributes
that specify its size:
### height
This specifies the height of the
image in pixels.
### width:
This specifies the width of the
image in pixels.
Images often take longer to
load than the HTML code that
makes up the rest of the page.
It is, therefore, a good idea to
specify the size of the image
so that the browser can render
the rest of the text on the page
while leaving the right amount of
space for the image that is still
loading.


The align attribute can take
these horizontal values:
left
This aligns the image to the left
(allowing text to flow around its
right-hand side).
right
This aligns the image to the right
(allowing text to flow around its
left-hand side).

There are three values that the
align attribute can take that
control how the image should
align vertically with the text that
surrounds it:
top
This aligns the first line of the
surrounding text with the top of
the image.
middle
This aligns the first line of the
surrounding text with the middle
of the image.
bottom
This aligns the first line of the
surrounding text with the bottom
of the image.

Image Dimensions
The images you use on your website should be
saved at the same width and height that you
want them to appear on the page.


Image Resolution
Images created for the web should be saved at
a resolution of 72 ppi. The higher the resolution
of the image, the larger the size of the file.


Vector Images
Vector images differ from bitmap images and
are resolution-independent. Vector images are
commonly created in programs such as Adobe
Illustrator.

Figure Caption
<figure>
Images often come with
captions. HTML5 has introduced
a new <figure> element to
contain images and their caption
so that the two are associated.
You can have more than one
image inside the <figure>
element as long as they all share
the same caption.
  
  Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.


Color not only brings your s XX ite to life, but also helps
convey the mood and evokes reactions.

There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.

Color pickers can help you find the color you want.
 It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
 CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
 CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.




The properties that allow you to control
the appearance of text can be split into
two groups:
Those that directly affect t ●● he font and its appearance
(including the typeface, whether it is regular, bold or italic,
and the size of the text)
●● Those that would have the same effect on text no matter
what font you were using (including the color of text and
the spacing between words and letters)


  















