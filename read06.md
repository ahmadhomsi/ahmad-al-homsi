

we need to take about Why problem domains are hard

* the problem domain, or making it so trivial that it is easily understood, I am able to make both teaching and learning easier

* As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

* If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

Make the problem domain easier
Get better at understanding the problem domain

* chapter 3

WHAT IS AN OBJECT?

Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 


This object represents a hotel. It has five properties and one method.
The object is in curly braces. It is stored in a variable called hotel .

In JavaScript:
• Variables have a name and you can assign them a
value of a string, number, or Boolean.
• Arrays have a name and a group of values. (Each
item in an array is a name/value pair because it
has an index number and a value.)
• Named functions have a name and value that is a
set of statements to run if the function is called.
• Objects consist of a set of name/value pairs
(but the names are referred to as keys). 


* The only things changing in the
code are the values of the hot e 1
object's properties:
• The name of the hotel
• How many rooms it has
• How many rooms are booked
The rest of the page works in
exactly the same way. The name
is shown using the same code.
The checkAvai 1 abi l ity()
method has not changed and is
called in the same way

Chapter 5
The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window

THE DOCUMENT NODE
Above, you can see the HTML code for a shopping
list, and on the right hand page is its DOM tree.
Every element, attribute, and piece of text in the
HTML is represented by its own DOM node.
At the top of the tree a document node is added; it
represents the entire page (and also corresponds to
the document object, which you first met on p36).
When you access any element, attribute, or text
node, you navigate to it via the document node. It is
the starting point for all visits to the DOM tree.
s DOCUMENT OBJECT MODEL
* ELEMENT NODES
HTML elements describe the structure of an HTML
page. The h l > - h6> elements describe what
parts are headings; the p> tags indicate where
paragraphs of text start and finish; and so on.)
To access the DOM tree, you start by looking for
elements. Once you find the element you want, then
you can access its text and attribute nodes if you
want to. This is why you start by learning methods
that allow you to access element nodes, before
learning to access and alter text or attributes. 

* Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes. 
* The terms elements and element nodes are used interchangeably
but when people say the DOM is working with an element,
it is actually working with a node that represents that element. 
* DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes. 
* A Nodelist is a collection of element nodes. Each
node is given an index number (a number that starts
at zero, just like an array).
The order in which the element nodes are stored in a
Node List is the same order that they appeared in the
HTML page.
When a DOM query returns a Nodelist, you may
want to:
• Select one element from the NodeList.
• Loop through each item in the Nodelist and
perform the same statements on each of the
element nodes. 

* SELECTI NG ELEMENTS
USING CLASS ATTRIBUTES
The get El ementsByCl ass Name()
method allows you to select
elements whose c 1 ass attribute
contains a specific value.
c05/js/get-elements-by-class-name .js
The method has one parameter:
the class name which is given
in quotes within the parentheses
after the method name.
Because several elements can
have the same value for their
cl ass attribute, this method
always returns a Nodelist

* If you want to apply the same
code to numerous elements,
looping through a Nodelist is a
powerful technique.
JAVASCRIPT
It involves finding out how many
items are in the Nodelist, and
then setting a counter to loop
through them, one-by-one.
Each time the loop runs, the
script checks that the counter
is less than the total number of
items in the Nodelist. 

* When you have an element node, you can select
another element in relation to it using these five
properties. This is known as traversing the DOM.

* Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across whitespace between elements

* So far this chapter has focused on finding elements in the DOM tree.
The rest of this chapter shows how to access/update element content.
Your choice of techniques depends upon what the element contains.

* DOM manipulation can be used to remove
elements from the DOM tree.


* DISADVANTAGES
• It only works when the page initially loads.
• If you use it after the page has loaded it can:
1. Overwrite the whole page
2. Not add the content to the page
3. Create a new page
• It can cause problems with XHTML pages that
are strictly validated.
• This method is very rarely used by programmers
these days and is generally frowned upon. 












