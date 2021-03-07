# Objects 


Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

### IN AN OBJECT: VARIABLES BECOME
KNOWN AS PROPERTIES

### IN AN OBJECT: FUNCTIONS BECOME
KNOWN AS METHODS

![image](https://user-images.githubusercontent.com/79080942/110242671-cb0a4280-7f5f-11eb-9fcb-93a5bddae9ff.png)


![image](https://user-images.githubusercontent.com/79080942/110242691-de1d1280-7f5f-11eb-8c3c-09f292cf12f3.png)


The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.





THE DOM TREE IS A
MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.


![image](https://user-images.githubusercontent.com/79080942/110242732-0a389380-7f60-11eb-8bb6-01554385f4af.png)



WORKING WITH
THE DOM TREE
Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes.

METHODS THAT RETURN A SINGLE ELEMENT NODE:
getElementByld( ' id ')
Selects an individual element given the value of its i d attribute .
The HTML must have an id attribute in order for it to be selectable.
First supported: IE5.5, Opera 7, all versions of Chrome, Firefox, Safari.
querySel ector( 1css selector ')
Uses CSS selector syntax that would select one or more element s .
This method returns only the first of the matching elements.
First supported: IE8, Firefox 3.5, Safari 4. Chrome 4, Opera 10
getEl ement sByClassName( 1class 1
)
Selects one or more elements given the va lue of their cl ass attribute.
The HTML must have a cl ass attribu te for it to be selectable.
This method is faster than querySe 1ectorA11 () .
First supported: IE9, Firefox 3, Safari 4, Chrome 4, Opera 10
(Several browsers had partial I buggy support in earlier versions)
getEl ementsByTagName( 1 tagName 1
)
Selects all elements on the page with the specified tag name.
This method is faster than querySe 1ectorA11 ().
First supported: IE6+, Firefox 3, Safari 4, Chrome, Opera 10
(Several browsers had partial I buggy support in earlier versions)
querySelectorAll ( 1css select or •)
Uses CSS selector syntax to select one or more elements and returns all
of those that match.
First supported: IE8, Firefox 3.5, Safa ri 4, Chrome 4, Opera 10



ADDING ELEMENTS USING
DOM MANIPULATION
DOM manipulation offers another technique
to add new content to a page (rather than
i nnerHTML). It involves three steps:

1. CREATE THE ELEMENT
createEl ement ()
You start by creating a new
element node using the
createElement() method.
This element node is stored
in a variable.
When the element node is
created, it is not yet part of the
DOM tree. It is not added to
the DOM tree until step 3.
In the example at the end of the
chapter, you will see another
method that can be used to
insert an element into the DOM
tree. The i nsertBefore ()
method is used to add a new
element before the selected
DOM node.

2. GIVE IT CONTENT ADD IT TO THE DOM
createTextNode() appendChild()
createTextNode() creates a Now that you have your element
new text node. Again, the node (optionally with some content
is stored in a variable. It can be in a text node), you can add
added to the element node using it to the DOM tree using the
the appendChi l d () method. appendChi 1 d () method.
This provides the content for the The appendChi 1 d () method
element, although you can skip allows you to specify which
this step if you want to attach an element you want this node

ADD IT TO THE DOM
createTextNode() appendChild()
createTextNode() creates a Now that you have your element
new text node. Again, the node (optionally with some content
is stored in a variable. It can be in a text node), you can add
added to the element node using it to the DOM tree using the
the appendChi l d () method. appendChi 1 d () method.
This provides the content for the The appendChi 1 d () method
element, although you can skip allows you to specify which
this step if you want to attach an element you want this node
empty element to the DOM tree. added to, as a child of it.


![image](https://user-images.githubusercontent.com/79080942/110242928-dca01a00-7f60-11eb-8fb3-bcf918d996c7.png)







