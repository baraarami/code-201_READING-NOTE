
# Table 
A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

(table)
The <table> element is used
to create a table. The contents
of the table are written out row
by row.
(tr)
You indicate the start of each
row using the opening <tr> tag.
(The tr stands for table row.)
It is followed by one or more
(td) elements (one for each cell
in that row).
At the end of the row you use a
closing (/tr) tag.
(td)
Each cell of a table is
represented using a (td)
element. (The td stands for
table data.)
At the end of each cell you use a
closing (/td) tag.


The <th> element is used just
like the <td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)
Even if a cell has no content,
you should still use a <td> or
<th> element to represent
the presence of an empty cell
otherwise the table will not
render correctly. (The first cell
in the first row of this example
shows an empty cell.)
Using <th> elements for
headings helps people who
use screen readers, improves
the ability for search engines
to index your pages, and also
enables you to control the
appearance of tables better
when you start to use CSS.
You can use the scope attribute
on the <th> element to indicate
whether it is a heading for a
column or a row. It can take the
values: row to indicate a heading
for a row or col to indicate a
heading for a column.

(thead)
The headings of the table should
sit inside the <thead> element.
(tbody)
The body should sit inside the
(tbody) element.
(tfoot)
The footer belongs inside the
(tfoot) element.
By default, browsers rarely treat
the content of these elements
any differently than other
elements however designers
often use CSS styles to change
their appearance.
  
You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.  



![image](https://user-images.githubusercontent.com/79080942/110243195-073ea280-7f62-11eb-88e1-cead1e801df7.png)


Sometimes you will want several objects to represent similar things.
Object constructors can use a function as a template for creating objects.
First, create the template with the object's properties and methods.
![image](https://user-images.githubusercontent.com/79080942/110243221-1f162680-7f62-11eb-85f8-d68385da9488.png)


THIS (IT IS A KEYWORD)
The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates.

A FUNCTION IN GLOBAL SCOPE
When a function is created at the top level of a script
(that is, not inside another object or function), then it
is in the global scope or global context.
The default object in this context is the window
object. so when this is used inside a function in the
global context it refers to the window object.


GLOBAL VARIABLES
All global variables also become properties of the
window object. so when a function is in the global
context, you can access global variables using the
window object, as well as its other properties.


RECAP: STORING DATA
In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key.


VARIABLES
A variable has just one key (the variable name)
and one va lue.

ARRAYS
Arrays can store multiple pieces of information.
Each piece of information is separated by a comma.
The order of the values is important because items
in an array are assigned a number (called an index).


If you want to access items via a property name or key, use an object
(but note that each key in the object must be unique).
If the order of the items is important, use an array.











