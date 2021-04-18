# Domain Modeling

Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.


* A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

* Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

Here's some tips to follow when building your own domain models.

* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

* Model its attributes with a constructor function that defines and initializes properties.

* Model its behaviors with small methods that focus on doing one job well.

* Create instances using the new keyword followed by a call to a constructor function.

* Store the newly created object in a variable so you can access its properties and methods from outside.

* Use the this variable within methods so you can access the object's properties and methods from inside.


### From the Duckett HTML book:

## Chapter 6: “Tables” (pp.126-145)

* There are several types of information
that need to be displayed in a grid or
table. For example: sports results, stock
reports, train timetables.


* When representing information in a table, you need to think
in terms of a grid made up of rows and columns (a bit like a
spreadsheet). 

* In this chapter you will learn how to:

* Use the four key elements f  or creating tables
 Represent complex data using tables
Add captions to tables


* A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.



* table>
The  table> element is used
to create a table. The contents
of the table are written out row
by row.
* tr>
You indicate the start of each
row using the opening  tr> tag.
(The tr stands for table row.)
It is followed by one or more
td> elements (one for each cell
in that row).
At the end of the row you use a
closing  tr> tag.
* td>
Each cell of a table is
represented using a  td>
element. (The td stands for
table data.)
At the end of each cell you use a
closing /td> tag.



 * th>
The  th> element is used just
like the td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)

* thead>
The headings of the table should
sit inside the  thead> element.
* tbody>
The body should sit inside the
 tbody> element.
 tfoot>
The footer belongs inside the
tfoot> element.


* The table> element is used to add tables to a web
page.
*  A table is drawn out row by row. Each row is created
with the  tr> element.

*  Inside each row there are a number of cells
represented by the  td> element (or  th> if it is a
header).



# From the Duckett JS Book:

# Chapter 3: “Functions, Methods, and Objects” (pp.106-144)

* The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates. 

* In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 

* VARIABLES

A variable has just one key (the variable name)
and one value. 

* Browsers come with a set of built-in objects that represent things like the
browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages.

* An object model is a group of objects, each of
which represent related things from the real world.
Together they form a model of something larger.
Two pages back, it was noted that an array can hold
a set of objects, or that the property of an object
could be an array.

*  It is also possible for the property
of an object to be another object. When an object
is nested inside another object, you may hear it
referred to as a child object. 

* Whenever you have a value that is a string, you can use the properties
and methods of the String object on that value. This example stores the
phrase "Home sweet home " in a variable. 

* In JavaScript there are six data types:
Five of them are described as simple (or primitive) data types.
The sixth is the object (and is referred to as a complex data type)













