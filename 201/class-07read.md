

> # Domain Modeling

It is the process of creating a conceptual model that is made to solve problem or any reason, the model can describe various entity.
An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

General example 

var object model = function(proprity1, proprity2) {

  this. Object propriety = proprity1;

  this. Object propriety = proprity2;

}

var instance1 = new object name(7, false);

var instance2 = new object name(4, true);

console.log(instance1);

console.log(instance2);


This is object-oriented programming in JavaScript at its most fundamental level.

1.	The new keyword instantiates (i.e. creates) an object.
2.	The constructor function initializes properties inside that object using the (this) variable.
3.	The object is stored in a variable for later use.


> # Object model

Here are some properties of the
document object, which tell you
about the current page

PROPERTY | DESCRIPTION 
-------- | ----------
document.title | Title of current document 
document. l astModified | Date on which document was last modified
document .URL | Returns string containing URL of current document 
document.domain | Returns domain of current document

----

The following are a few of the
methods that select content or
update the content of a page.

METHOD | DESCRIPTION 
-------- | ----------
document.write()  | Writes text to document
document . getElementByld() | Returns element, if there is an element with the value of the id attribute that matches
document. querySe 1ectorA11 () | Returns list of elements that match a CSS selector, which is specified as a parameter
document.createElement()  |Creates new element
document.createTextNode() | Creates new text node


----
> # What's a Table?

A table represents information in a grid format.

Basic Table Structure

1. The `<table>` element is used
to create a table. The contents
of the table are written out row
by row.

2. `<tr>`
You indicate the start of each
row using the opening <tr> tag.
(The tr stands for table row.).

3. `<td>`
Each cell of a table is
represented using a `<td>`
element. (The td stands for
table data.)
At the end of each cell you use a
closing `</td>` tag.


> table headings

The `<th>` element is used just
like the `<td>` element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)

> ways to creat objecy

1. LITERAL NOTATION

var hotel = {}

hotel .name= 'Quay';

hotel .rooms = 40;

hotel.booked = 25;

hotel.checkAvailabil ity =function(){

return this.rooms - this .booked;

} ; 

2. OBJECT CONSTRUCTOR NOTATION

var hotel = new Object();

hotel .name = 'Quay';

hotel .rooms = 40;

hotel . booked= 25;

hotel.checkAvailability =function(){

return this .rooms - this.booked;

} ; 

> THIS keyword

The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates.
