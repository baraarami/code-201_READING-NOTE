# HTML Design and Build Websites


Before we look at the code used to build websites it is important to consider the different ways in which people access the web and clarify some terminology.

1. Browsers :
People access websites using software called a web browser. Popular examples include Firefox, Internet Explorer, Safari, Chrome, and Opera.

2. Web Servers :
When you ask your browser for a web page, the request is sent across the Internet to a special computer known as a web server which hosts the website.

3. Screen readers :
Screen readers are programs that read out the contents of a computer screen to a user. They are commonly used by people with visual impairments.

4. Devices :
People are accessing websites on an increasing range of devices including desktop computers, laptops, tablets, and mobile phones. It is important to remember that various devices have different screen sizes and some have faster connections to the web than others.


#### All websites use HTML and CSS, but content
management systems, blogging software, and e-commerce platforms often add a few more technologies into the mix.


# How Pages Use Structure
Think about the stories you read in a newspaper: for each story, there will be a headline, some text, and possibly some images. If the article is a long piece, there may be subheadings that split the story into separate sections or quotes from those involved. Structure helps readers understand the stories in the newspaper.The structure is very similar when a news story is viewed online (although it may also feature audio or video). This is illustrated on the right with a copy of a newspaper alongside the corresponding article on its website.


# Structuring Word Documents
The use of headings and subheadings in any document often reflects a hierarchy ofinformation. For example, a document might start with a large heading, followed by an introduction or the most important information. This might be expanded upon under subheadings lower down on the page. When using a word processor to create a document, we separate out the text to give it structure. Each topic might have a new paragraph, and each section can have a heading to describe what it covers.

# HTML Describes the Structure of Pages

HTML Uses Elements to Describe the Structure of Pages
1. (h1) :This is the Main Heading(/h1)
2. (p) :This text might be an introduction to the rest of
the page. And if the page is a long one it might
be split up into several sub-headings.(/p)
3. (h2) :This is a Sub-Heading(/h2)
4. (body): You met the <body> element
in the first example we created.
Everything inside this element is
shown inside the main browser
window.
 5. (head) :Before the <body> element you
will often see a <head> element.
This contains information
about the page (rather than
information that is shown within
the main part of the browser
window that is highlighted in
blue on the opposite page).
You will usually find a <title>
element inside the <head>
element.
6. (title) :The contents of the <title>
element are either shown in the
top of the browser, above where
you usually type in the URL of
the page you want to visit, or
on the tab for that page (if your
browser uses tabs to allow you
to view multiple pages at the
same time).

# Tags act like containers. They tell you
something about the information that lies
between their opening and closing tags.

# Attributes Tell Us More About Elements
Attributes provide additional information
about the contents of an element. They appear
on the opening tag of the element and are
made up of two parts: a name and a value,
separated by an equals sign.

To learn HTML you need to know what tags are
available for you to use, what they do, and where they
can go.


Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book.

# Comments in HTML
(!-- --)
If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:
(!-- comment goes here --)


# ID Attribute
Every HTML element can carry
the id attribute. It is used to
uniquely identify that element
from other elements on the
page. Its value should start with
a letter or an underscore (not a
number or any other character).
It is important that no two
elements on the same page
have the same value for their id
attributes (otherwise the value is
no longer unique).


# Class Attribute
Every HTML element can
also carry a class attribute.
Sometimes, rather than uniquely
identifying one element within
a document, you will want a
way to identify several elements
as being different from the
other elements on the page.
For example, you might have
some paragraphs of text that
contain information that is more
important than others and want
to distinguish these elements, or
you might want to differentiate
between links that point to other
pages on your own site and links
that point to external sites.

# Block Elements
Some elements will always
appear to start on a new line in
the browser window. These are
known as *block level* elements.
(*Examples of block elements are
(h1), (p), (ul), and (li).*)

# Inline Elements
Some elements will always
appear to continue on the
same line as their neighbouring
elements. These are known as
inline elements.
(*(a), (b), (em), and (img).*)

# Grouping Text & Elements In a Block
(div) : element allows you to
group a set of elements together
in one block-level box.
For example, you might create
a <div> element to contain all
of the elements for the header
of your site (the logo and the
navigation), or you might create
a (div) element to contain
comments from visitors.

# Grouping Text & Elements Inline
The (span) element acts like
an inline equivalent of the (div)
element. It is used to either:
1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
2. Contain a number of inline
elements

#### The most common reason why
people use (span) elements
is so that they can control the
appearance of the content of
these elements using CSS.

# IFrames
An iframe is like a little window
that has been cut into your
page — and in that window you
can see another page. The term
iframe is an abbreviation of inline
frame. One common use of iframes
(that you may have seen on
various websites) is to embed
a Google Map into a page. The
content of the iframe can be any
html page (either located on the
same server or anywhere else on
the web).
An iframe is created using the
<iframe> element. There are a
few attributes that you will need
to know to use it:
**src**
The src attribute specifies the
URL of the page to show in the
frame.
**height**
The height attribute specifies
the height of the iframe in pixels.
**width**
The width attribute specifies
the width of the iframe in pixels.


# Information About Your Pages we use :
The (meta) element lives
inside the (head) element and
contains information about that
web page.
It is not visible to users but
fulfills a number of purposes
such as telling search engines
about your page, who created
it, and whether or not it is time
sensitive. (If the page is time
sensitive, it can be set to expire.)

The (meta) element is an empty
element so it does not have a
closing tag. It uses attributes to
carry the information.
 
The value of the name attribute
can be anything you want it to
be. Some defined values for this
attribute that are commonly
used are:
1. description :
This contains a description
of the page. This description
is commonly used by search
engines to understand what the
page is about and should be a
maximum of 155 characters.
Sometimes it is also displayed in
search engine results. 

2. keywords :
This contains a list of commaseparated
words that a user
might search on to find the page.
In practice, this no longer has
any noticeable effect on how
search engines index your site.

3. robots :
This indicates whether search
engines should add this page
to their search results or not. A
value of noindex can be used if
this page should not be added. A
value of nofollow can be used
if search engines should add this
page in their results but not any
pages that it links to. 

4. author :
This defines the author of the
web page.

5. pragma :
This prevents the browser from
caching the page. (That is,
storing it locally to save time
downloading it on subsequent
visits.)

6. expires :
Because browsers often cache
the content of a page, the
expires option can be used
to indicate when the page
should expire (and no longer be
cached). Note that the date must
be specified in the format shown.

###### Escape characters are used to include special
characters in your pages such as "<, >", and "©".



# HTML5 is introducing a new set of
elements that help define the structure of
a page.
For a long time, web page authors used <div> elements to group
together related elements on the page (such as the elements that form a
header, an article, footer or sidebar). Authors used class or id attributes
to indicate the role of the <div> element in the structure of the page.
  
  
  
  
 # Headers & Footers
 The (header) and (footer)
elements can be used for:
* The main header or footer
that appears at the top or
bottom of every page on the
site.
* A header or footer for an
individual <article> or
(section) within the page.
  
 
 # Navigation
 The (nav) element is used to
contain the major navigational
blocks on the site such as the
primary site navigation.
  
 # Articles
 The (article) element acts as
a container for any section of a
page that could stand alone and
potentially be syndicated.
This could be an individual
article or blog entry, a comment
or forum post, or any other
independent piece of content.


# ASIDES
The (aside) element has two
purposes, depending on whether
it is inside an (article)
element or not.
When the (aside) element
is used inside an (article)
element, it should contain
information that is related to the
article but not essential to its
overall meaning. For example, a
pullquote or glossary might be
considered as an aside to the
article it relates to.
When the (aside) element is
used outside of an (article)
element, it acts as a container
for content that is related to
the entire page. For example,
it might contain links to other
sections of the site, a list of
recent posts, a search box, or
recent tweets by the author.


# Sections
The (section) element groups
related content together, and
typically each section would
have its own heading.


# Heading Groups
The purpose of the (hgroup)
element is to group together a
set of one or more (h1) through
(h6) elements so that they are
treated as one single heading.
  
# Figures
You already met the (figure)
element in Chapter 5 when we
looked at images. It can be used
to contain any content that is
referenced from the main flow of
an article (not just images).
It is important to note that the
article should still make sense
if the content of the (figure)
element were moved (to another
part of the page, or even to a
different page altogether).

Examples of usage include:
* Images
* Videos
* Graphs
* Diagrams
* Code samples
* Text that supports the main
body of an article


# Sectioning Elements ("div")
It may seem strange to follow
these new elements by revisiting
the <div> element again. (After
all, the new elements are often
going to be used in its place.) 
  
Some people have asked why
there is no (content) element
to contain the main part of
a page. The reason is that
anything that lies outside of the
(header), (footer) or (aside)
elements can be considered as
the main content.
  
# Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.  
  
Now that you know who your visitors are, you
need to consider why they are coming. While
some people will simply chance across your
website, most will visit for a specific reason.
  
You know who is coming to your site and why
they are coming, so now you need to work out
what information they need in order to achieve
their goals quickly and effectively.
Here are some questions to help
you decide what information to
provide for visitors to your site...

1. Will visitors be familiar with
your subject area / brand
or do you need to introduce
yourself?

2. Will they be familiar with
the product / service /
information you are covering
or do they need background
information on it?

3. What are the most important
features of what you are
offering?
4. What is special about what
you offer that differentiates
you from other sites that offer
something similar?
5. Once people have achieved
the goal that sent them to
your site, are there common
questions people ask about
this subject area?



# Site Maps
Now that you know what needs to appear
on your site, you can start to organize the
information into sections or pages.


# WireFrames
A wireframe is a simple sketch of the key
information that needs to go on each page of a
site. It shows the hierarchy of the information
and how much space it might require.

![image](https://user-images.githubusercontent.com/79080942/109397049-62a6da00-793d-11eb-843d-390702babf05.png)


# Visual hierarchy
Most web users do not read entire pages. Rather, they skim to find
information. You can use contrast to create a visual hierarchy that gets
across your key message and helps users find what they are looking for.

# You can differentiate between pieces of information
using size, color, and style.

# You can use grouping and similarity to help simplify
the information you present.


learning to program with *JavaScript* involves :
1. understanding some basic programming concepts and the terms that javascript programmers use to describe them .
2. learning the language itself , and like all languages , you need to know it's vocabulary and how to structure your sentences .
3.becomeing familier with how it's applied by looking at examples commonly used in websites today.


# Before you learn how to read and write the javascript language itself , you need to becone familiar with some key concepts 
in computer programing . they will be converedin three sections:
* A :
 What is a consipt and hoe do I creat one ?
 * B :
 how do computers fit in with the world around them ?
 * C :
 how do I write a script for a web page ?
 
 
 # what is script ?
 it's a series of instructions that a computer can follow to achive a goal .
 to write a script , you need to first state your goal and then list the tasks that need to be copleted in order to achive it .
 
 start with the big picture of what you want to achive , and break that down into smaller steps .
 1. Define the coal .
 2. Design the script .
 3. Code each step .
 
To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task (a flowchart can help).

# how do computers fit in with world around them !
1. computers creats models of the world using data .
2. the models yse object to represent physical things 
3. programmers can write code says "when this event occurs run that code"
4. web browsers use HTML markup to creat a model of the web pages . each element creats it's own node .
5. to make web pages interactive , you write code that uses the browsers model of the web page .

# HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER
![image](https://user-images.githubusercontent.com/79080942/109397869-be736200-7941-11eb-90e9-3ab8ace64c87.png)




# how do i write a script for a web page ?
1. It is best to keep JavaScript code in its own JavaScript
file. JavaScript files are text files (like HTML pages and
CSS style sheets), but they have the . j s extension.

2. The HTML <script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the (link) element can be used to load a CSS file).

3. If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
page that the browser has created.





























































































