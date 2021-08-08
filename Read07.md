# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
###  object-oriented programming in JavaScript at its most fundamental level
1. The ```new```  keyword instantiates (i.e. creates) an object.
2. The constructor function initializes properties inside that object using the ```this ``` variable.
3. The object is stored in a variable for later use.

## Generate random numbers
 the JavaScript standard library includes a ```Math.random()``` function
 ```
var EpicFailVideo = function(epicRating, hasAnimals) {
  this.epicRating = epicRating;
  this.hasAnimals = hasAnimals;
}

EpicFailVideo.prototype.generateRandom = function(min, max) {
  return Math.floor(Math.random() * (max - min + 1)) + min;
}

var parkourFail = new EpicFailVideo(7, false);
var corgiFail = new EpicFailVideo(4, true);

console.log(parkourFail.generateRandom(1, 5));
console.log(corgiFail.generateRandom(1, 5));
 ```
 As you can see, methods can be added to a constructor function's prototype. Think of the prototype as an object's stunt double

we can also model domain for 
* Calculate daily random numbers
* Calculate weekly random numbers

 ## summary 
 Domain modeling is the process of creating a conceptual model for a specific problem

 tips to follow when building your own domain model: 
 * When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
 * Model its attributes with a constructor function that defines and initializes properties.
 * Model its behaviors with small methods that focus on doing one job well.
 * Create instances using the ```new``` keyword followed by a call to a constructor function.
 * Store the newly created object in a variable so you can access its properties and methods from outside.
 * Use the ```this``` variable within methods so you can access the object's properties and methods from inside.

 # Chapter 6: Tables
When representing information in a table, you need to think in terms of a grid made up of rows and columns
There are several types of information
that need to be displayed in a grid or
table. 

For example:

* Use the four key elements f ●● or creating tables
* Represent complex data using tables
* Add captions to tables

## What's a Table?
A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

## points the chapters mentions  
1. The ```<table>``` element is used to add tables to a web page.
2. A table is drawn out row by row. Each row is created
with the ```<tr>``` element. 3. Inside each row there are a number of cells represented by the ```<td>``` element (or ```<th>``` if it is a header).
4. You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
5. For long tables you can split the table into a ```<thead>```, ```<tbody>```, and ```<tfoot>```.\

# Chapter 3: Functions, Methods, and Objects
returning to this chapter to  to continue discuss Functions, Methods, and Objects

## Creating an object : Constructor notation
the new keyword and object constructor create a blank object. you can the add properties and methods to the ojbject.

### we can also update the object 
to update the value of the properties, we use dot notation or square brackets they work on objects created using literal or constructor notation. to delete a property, use the ```delete``` keyword

### CREATING MANY OBJECTS: CONSTRUCTOR NOTATION
Sometimes you will want several objects to represent similar things.

Object constructors can use a function as a template for creating objects.

## This chapter also talks about 
* CREATING OBJECTS USING CONSTRUCTOR SYNTAX
* CREATE & ACCESS OBJECTS CONSTRUCTOR NOTATION
* ADDING AND REMOVING PROPERTIES

## Arrays are objects 
**Arrays** are actually a special type of object, they hold a related set of key/value pairs(like all objects), but the key for each value is its index number.

## WHAT ARE BUILT-IN OBJECTS?
Browsers come with a set of built-in objects that represent things like the
browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages.
The first thing you need to do is get to know what tools are available.
You can imagine that your new toolkit has three compartments:
1. BROWSER OBJECT MODEL
2. DOCUMENT OBJECT MODEL
3. GLOBAL JAVASCRIPT OBJECTS

JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
also Arrays and objects can be used to create complex data
sets (and both can contain the other).
