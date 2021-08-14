# Chapter 7: Forms

Traditionally, the term 'form' has referred
to a printed document that contains
spaces for you to fill in information.

In this chapter you will learn:

1. How to create a form on your website
2. The different tools for collecting data
3. New HTML5 form controls

## Why Forms?

The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage.

## Form Controls

There are several types of form controls that
you can use to collect information from visitors
to your site.

* ADDING TEXT
* Ma king Choices
* Submitting Forms
* Uploading Files

## How Forms Work

A user fills in a form and then presses a button
to submit the information to the server.

A form may have several form controls, each
gathering different information. The server
needs to know which piece of inputted data
corresponds with which form element.

## important point that chapter 7 talks about

* Whenever you want to c XX ollect information from
visitors you will need a form, which lives inside a
```<form>``` element.
* Information from a form is sent in name/value pairs.
* Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
* HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

# Chapter 14: Lists, Tables and Forms

There are several CSS properties that
were created to work with specific types
of HTML elements, such as lists, tables,
and forms.

In this chapter you will learn how to:

* Specify the type of bullet p ●● oint or numbering on lists
* Add borders and backgrounds to table cells
* Control the appearance of form controls

## style of lists

* Bullet point styles
* Images for bullets
* Positioning the marker
* List shorthand

## Styling Forms

Nobody I know enjoys filling in forms, so if you can make yours look more attractive and easier to use, more people are likely to fill it in.  lso, when you come to look at a form in a few different  rowsers (as shown on the right), you will see that each  rowser displays them differently.

### most common style

* Text inputs and text areas
* Submit buttons
* Labels on forms, to get the form controls to align nicely

## important point that chapter 14 talks about

* In addition to the CSS p XX roperties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms
* List markers can be given different appearances
using the list-style-type and list-style image
properties.
* Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
* Forms are easier to use if the form controls are
vertically aligned using CSS.
* Forms benefit from styles that make them feel more
interactive.

# Chapter 6: Events

When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.

## DIFFERENT EVENT TYPES

* UI EVENTS
* KEYBOARD EVENTS
* MOUSE EVENTS

## TERMINOLOGY

* EVENTS FIRE OR ARE RAISED
When an event has occurred, it is often described as having fired or
been raised. In the diagram on the right, if the user is tapping on a link, a
click event would fire in the browser.
* EVENTS TRIGGER SCRIPTS
Events are said to t rigger a function or script. When the click event fires on the element in this diagram, it could trigger a script that enlarges the selected item.

## HOW EVENTS TRIGGER JAVASCRIPT CODE

When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling.

1. Select t he element
node(s) you want the
script to respond to.
2. Indicate which event on
the selected node(s) will
trigger the response.
3. State the code you want
to run when the event
occurs.

## THREE WAYS TO BIND AN EVENT TO AN ELEM ENT

Event handlers let you indicate which event you
are waiting for on any particular element.
There are three types of event handlers.

1. HTML EVENT HANDLERS ```(DO NOT USE)```
2. TRADITIONAL DOM EVENT HANDLERS
3. DOM LEVEL 2 EVENT LISTENERS

## SUPPORTING OLDER VERSIONS OF IE

IES-8 had a different event model and did not support
addEventL i stener() but you can provide fallback code
to make event listeners work with older versions of IE.

## this chapter also discuss

* Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
* Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
* When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
* You can use event delegation to monitor for events
that happen on all of the children of an element.
* The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.
