# Links

Links allows us to surf the web making us move from one web page to another

## common types of links :
* links from one website to another
* Links from one page to another on the same website
* Links from one part of a web page to another part of the
same page
* Links that open in a new browser window
* Links that start up your email program and address a new
email to someone

## Writing links 

Links are created by using ```<a>``` element where anything between them are clickable

### linking to other sites

Use ```<a>``` and put the URL in an attribute called href.
example : 
```
<a href="http://www.rottentomatoes.com">
Rotten Tomatoes</a>
```
## Links from one page to another on the same website

Same as link to another site
But you don’t have to give domain name in url you can use what’s known as a relative URL
example :
```
<a href="index.html">Home</a>
```

### Relative URLs

Are used when linking pages from when you own website .

## Email links
mailto : we add the add mailto to our element ```<a>```  so the user\’s email program address an email specified to that email address 
Example :
```
<a href="mailto:addressn@example.org">Email address</a>
```

## Links that open in a new browser window
###target
If you want to open a new browser for the link we add target to our ```<a>```
Example 
```
<a href="http://www.imdb.com" target="_blank">
Internet Movie Database</a>
```

# layout 
This part goes on the different ways to position elements using normal flow ,relative positioning,absolute positioning and floats andand how different size and resolution affects the design process and learn the difference between width and liquid layouts and how they are created , and find out how designer use grids to make their page to look more professional 

## key concepts in positioning elements
CSS trasts HTML elements as boxes the boxes will be either block- level box or inline box 

* block-level elements starts on a new line.
* inline elements flow in between surrounding text.

## Containing elements 

If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.

## Controlling the position of elements 

CSS give you 3 positioning scheme that you can specify 
* normal flow
* relative positioning 
* absolute positioning 

To indicate where a box should be positioned, you may also need to use
box offset
* Fixed Positioning
* Floating Elements

## Screen Size 

Each user has a different size screen that will show different sizes of information. Our design has to keep that in mind.

## Screen Resolution

Refers to the number of dots per inch some have high other have low desktops can even offer options 

## Page size 

Designer try to create pages around 960-100 pixels since screen size and display resolution vary so much 

# Functions, Methods, and Objects

tthese are what programmers use to orgainze their code and give instructions

## WHAT IS A FUNCTION?

it is group of statements that work together to perform a task

## WHAT IS AN OBJECT?
is set of variables creating something that you would use in real life 

## WHAT IS AN METHOD?
it represents how pople will interact with an object in real life  

# 6 Reasons for Pair Programming
The article talks about the benefits of working in a pair and how they have dramatically improved the quality of their code and how does it work and why should we try it, they made a list 

 * Greater efficiency

    talks about How people have this misconception about working in paris 
 * Engaged collaboration

    Talks about how when they are more than one person working on a code they are likely to be more forced and giving a conscious effort 
 * Learning from fellow students

    Since people have different skills they are bond to look at a problem differently so they learn from each other 
 * Social skills

    Talks about how difficult it can get when two different personality works together thats why having good social skills will help us communicate better and they only way to improve it is by socializing 
 * Job interview readiness

    a common interview process is pair programming to tests your communication skills as it is important for a compy to be able to say on the same page 
 * Work environment readiness

    Many companies pair new hires with already familiar programmers to help them settle in with the work 