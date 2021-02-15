# Object-Oriented Programming, HTML Tables
----------------------
## Domain Modeling

**Domain** modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

When we building domain models:

1-When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

2-Model its attributes with a constructor function that defines and initializes properties.

3-Model its behaviors with small methods that focus on doing one job well.

4-Create instances using the new keyword followed by a call to a constructor function.

5-Store the newly created object in a variable so you can access its properties and methods from outside.

6-Use the this variable within methods so you can access the object's properties and methods from inside.

------------------------------------

## Chapter 6 (from Duckett HTML book )

code  | It work
-------- |----------
table |to create a table. The contents of the table are written out row by row.
tr|each row should be strating with it
td|Each cell of a table is represented using it 
th|defines a table heading

Spanning Column (colspan="#") #:the number of cells in column spanning

Spanning Row (rowspan="#") #:the number of cells in row spanning

-----------------------------------
## Chapter 3 (From the Duckett JS book)

creating objects using constructor syntax

function Hotel (name, rooms, booked) {

this.name = name;

this.rooms = rooms;

this.booked = booked;

this.checkAvailability = function()

return this.rooms - this.booked;

} ;

or you can use :

var hotel = new Object();

hotel.name= 'Park';

hotel.rooms = 120;

hotel .booked = 77;

hotel .checkAvailability = function()

return this.rooms - this.booked;

} ; 

* to Removing properties delete function name.objective items;

* we use this when we still inside the objecte

* The array special type of object




        
