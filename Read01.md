# Introductory HTML and JavaScript
## Structure
Will be looking at how HTML deceptive webpages and learn tags and elements to make our first web page.

How pages use structures 

Similar to newspapers we have headers ,title ,main articles and images and if the article is long we might even have subtitles and web pages are very similar even though we might have videos and audios.

Code example :
``` <html>
<body>
 <h1>This is the Main Heading</h1>
 <p>This text might be an introduction to the rest of
 the page. And if the page is a long one it might
 be split up into several sub-headings.<p>
 <h2>This is a Sub-Heading</h2>
 <p>Many long articles have sub-headings so to help
 you follow the structure of what is being written.
 There may even be sub-sub-headings</p>
 </body>
</html>
```
The code in <> is made of characters called HTML elements made of two tags opening and closing </> each of tell the browser something and where it start and ends and the informations it contains

 ```<body>```
Everything inside this element is shown inside the main browser window.

```<head> ```

Before the ```<body> ```will often see ```<head> ```element This contains information about the page

```<title>```

Usually shown in the top of the browser above where you usually type the URL or on tabs for that page if the webpages uses tabs 

## Extra Markup

Will focus on some helpful topics to make page feels more fresh 


The different versions of HTML(we are will be using 5)
* How to add comments 
* Globe attributes that can be used in any elements 
* Elements to group together parts of the page where no elements are suitable 
* How to embed page within page using iframes 
* How to add information about page using ```<meta>``` element
* Adding characters 

### The different versions of HTML

With each new version design comes improvements on the one before with new elements and attribute added and older code removed there have been several the most notable are HTML 4, XHTML10 and HTML5 (which is the one we’ll be focusing on) where web page authors do no need to close all tags, and new elements and attributes was introduced the HTML 5 specification has not been completed but the major browser makers had started to implement the new features and many authors are adopting the new markup, even tho it’s incomplete you can still take advantage of HTML5.

## HTML5 Layout

Will be taking about important elements in creating the layout. 

* New HTML5 layout elements and their use
* How they offer help as alternative to the ```<div>``` element
* How to make sure the browser recognize these elements 

For a long time , ```<div>``` was used by web page authors to group together elements on pages (body,title,header,sidebar), HTML5 introduce new set of element allowing us to divide the page to parts even tho it is subject to change that didn’t stop author from adopting and using them.

### ```<header> <footer>```

They appear at the top or the bottom of every page , header can contain the site name and navigation and the footer can contain copyright information and each ```<article>``` and ```<section>``` has their own header and footer elements 

### ```<nav>```

Contain the major navigational blocks on the site and if you were to end it with a link to relate blog posts it wouldn’t be navigational l block so therefore they don’t belong here inside the ```<nav>``` element .

### ```<article>```

Here we can contain any section of that page that could stand alone. This could be an invidal article or blog entry ,comment or forum post if a page has multiple pages, they each should have their own individual article.

### ```<div>```
May it be strange to follow these new elements by revisiting ```<div>``` however ```<div>``` remains an important way to group related elements because you shouldn't be using the new elements you have for a purpose that they dont stand for. That's where you can still use ```<div>``` to group them.

## Process & Design

We’ll be discussing the process that we can use when we are creating a new website. We'll be looking at who might visit the website and look at design theory to create a professional looking website.

* Understanding the audience
* Recognizing the information that the visitor wants to see
* Design theory to presenting the information 
* Design tips to create more creative and professional websites  

### who is the site for

Understanding that every site should be designed for the target audience not just for yourself or the owners.

It’s help full to ask yourself some question about the people who might be interested in the subject of the website ,it’s common when you ask a client whose site is target at the answer “ the entire world “ let’s be real that very unrealistic if your site sells card games no way an a mom in her 40s would be interested so it’s very unlikely she order some cards even if they site has wide apple you should be able to think of demographic target.

### why people visits 

Understanding why people might come to the website be it they are looking to achieve some goal or buy something or even mindless entertainment it’s important to understand the appeal  

### using design to get your message 

The primary aim of your visual design is should be to get the visitor engaged and to communicate the goal and prioritize making it easy for the visitor to understand the layout, having the webpage full of information left and right can be overwhelming and unwelcoming have few thing from the list can help you making easy to look at site:

* Masthead logo
* Links to navigate the site
* *Links to related content or popular articles 
* Login option or membership
* Ability for commenting 
* Copyright information 

# Quick summary of The ABC of programming

* A script is a series of instructions that the computer
can follow in order to achieve a goal.
* Each time the script runs, it might only use a subset of
all the instructions. 
* Computers approach tasks in a different way than
humans, so your instructions must let the computer
solve the task prggrammatically.
* To approach writing a script, break down your goal into
a series of tasks and then work out each step needed
to complete that task.


## thank you for reading my quick summary of what I read from Duckett HTML and Duckett JS books