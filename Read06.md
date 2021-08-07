# Understanding the problem domain 
The article reflects on the authors programming career and how he found the problem domains to be the hardest thing about programming 

## why problem domains are hard

The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all.

The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.

As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

## What can you do about it?

To make programming easier by :
* Make the problem domain easier
* Get better at understanding the problem domain

# Chapter 3: Object Literals

**What is an Object**

group together a set of variables and functions to create a model
of something you would recognize from the real world. In an object,
variables and functions take on new names.

# Chapter 5: Document Object Model
It specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window

## The DOM tree
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.

### Working with the DOM tree
Accessing and updating the DOM tree involves two steps:
* Locate the node that represents the element you want to work with.
* Use its text content, child elements, and attributes.


### Caching DOM queries 
Methods that find elements in the DOM tree are called DOM queries.
When you need to work with an element more than once, you should use a variable to store the result of this query 

### Accessing elements 
DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

### Traversing The DOM
When you have an element node, you can select
another element in relation to it using these five
properties. This is known as traversing the DOM.

#### Whitespace Nodes
Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across whitespace between elements


## HOW TO GET/UPDATE ELEMENT CONTENT
So far this chapter has focused on finding elements in the DOM tree.
The rest of this chapter shows how to access/update element content.
Your choice of techniques depends upon what the element contains.

To work with the content of elements you can:
* Navigate to the text nodes. This works best
when the element contains only text, no other
elements.

* Work with the containing element. This allows
you can access its text nodes and child elements.
It works better when an element has text nodes
and child elements that are siblings.

## REMOVING ELEMENTS VIA DOM MANIPULATION
DOM manipulation can be used to remove elements from the DOM tree
* STORE THE ELEMENT TO BE REMOVED IN AVARIABLE
* STORE THE PARENT OF THAT ELEMENT IN A VARIABLE
* REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT

## COMPARING TECHNIQUES: UPDATING HTML CONTENT
So far, you have seen three techniques for adding HTML to a web page.
It's time to compare when you should use each one.

You can choose different techniques depending on the task

**document.write()**

ADVANTAGES
* It is a quick and easy way to show beginners how
content can be added to a page

DISADVANTAGES
* It only works when the page initially loads.
* If you use it after the page has loaded it can:
1. Overwrite the whole page
2. Not add the content to the page
3. Create a new page
* It can cause problems with XHTML pages that
are strictly validated
* This method is very rarely used by programmers
these days and is genera lly frowned upon.

**element.innerHTML**

ADVANTAGES
* You can use it to add a lot of new markup using
less code than DOM manipulation methods.
* It can be faster than DOM manipulation when
adding a lot of new elements to a web page.
* It is a simple way to remove all of the content
from one element (by assigning it a blank string).

DISADVANTAGES
* It should not be used to add content that has
come from a user (such as a username or blog
comment), as it can pose a significant security
risk which is discussed over the next four pages.
* It can be difficult to isolate single elements
that you want to update within a larger DOM
fragment
* Event handlers may no longer work as intended.

**DOM MANIPULATION**

ADVANTAGES
* It is suited to changing one element from a DOM
fragment where there are many siblings.
* It does not affect event handlers.
* It easily allows a script to add elements
incrementally (when you do not want to alter a lot
of code at once).

DISADVANTAGES
* you have to make a lot of changes to the
content of a page, it is slower than i nnerHTML.
* You need to write more code to achieve the same
thing compared with i nnerHTML

## CROSS-SITE SCRIPTING (XSS) ATTACKS
If you add HTML to a page using i nnerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, an attacker could gain access to your users' accounts

### HOW XSS HAPPENS
XSS involves an attacker placing malicious code into
a site. Websites often feature content created by
many different people

### WHAT CAN THESE ATTACKS DO
XSS can give the attacker access to information in:
* The DOM (including form data)
* That website's cookies
* Session tokens: information that identifies you
from other users when you log into a site

This could let the attacker access a user account and:
* Make purchases with that account
* Post defamatory content
* Spread their malicious code further I faster

## Attribute Nodes
Once you have an element node, you can use other properties and methods on that element node to access and change its attributes

### CHECK FOR AN ATTRIBUTE AND GET ITS VALUES
Before you work with an attribute, it is good practice to check whether it exists. This will save resources if the attribute cannot be found.

### CREATING ATTRIBUTES & CHANGING THEIR VALUES
The cl assName property allows you to change the value of the cl ass attribute. If the attribute does not exist, it will be created and given the specified value. You have seen this property used throughout the chapter to update the status of the
list items. Below, you can see another way to achieve the task.

### REMOVING ATTRIBUTES
To remove an attribute from an element, first select the element, then call removeAttribute() . It has one parameter: the name of the attribute to remove. 

Trying to remove an attribute that does not exist will not cause an error, but it is good practice to check for its existence before attempting to remove it.

## EXAMINING THE DOM IN CHROME
Modern browsers come with tools that help you inspect the page loaded in the browser and understand the structure of the DOM tree

and each bowsers offer tools for viewing the DOM tree.