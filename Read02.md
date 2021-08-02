## Text

When creating a website, add tags to provide extra meaning to our content by allowing browser to shop the user the appropriate structure for the page 
We have two types 
* Structural markup: using the elements to describe both the headings and paragraphs.
* Semantic markup:provides extra information such as where emphasis is placed in a sentences and so on 

### Headings 
Html has six levels of heading each level have a different size and are bold used as the header for a point  ````<h1>````,````<h2>````,````<h3>````,````<h4>````,````<h5>````,````<h6>````
````<h1>```` is used for the main heading 
````<h2>```` is used for the subheadings
And if we want to even further subhead we use ````<h3>```` and so on.

### paragraphs
```<p>```
Is to create our paragraphs to fill in our content that we create by opening ```<p>``` and closing ```</p>``` each paragraph will start on a new line by default.

### Bold & Italic

We enclose the words between opening ```<b>``` closing ```</b>``` element toreporest the text in that section from being in bold and we use ```<i>``` ```</i>``` if we want the section to be in Italic.

### Superscript & subscript

* ``` <sup> ```element is used to contain characters that should be superscripted such as dates or mathematical concepts(such as raising a number to a power of 2)
* ```<sub>``` element is used to contain charatchs that should be subscript such as footnotes or chemical formulas 

### Line breaks & Horizontal rules 

```<br />``` we can use ```<br />``` to add a new line in a paragraph without creating a new one each time we need one.

```<hr />``` we use it to create a break between ideas and themes by using ```<hr />``` tag between the sections 

### Semantic markup

These elements don’t change the structure of your web page but they still add information.

### Strong & Emphasis
 
```<strong>```
The element is used to indicate the strong importance of the content by default the ```<strong>``` will show the element in bold.

```<em>```

The element is used to indicate emphasis that subtly change the meaning of the sentence by default ```<em>``` will show the element in italic

### Quotations
These two elements are used to quote content in markup

```<blockquote>```

The element is used to quote thing that take entire paragraph you might even see ```<p>``` inside the element. 

```<q>```

This element is also used to quote but it’s used for shorter quotes that sits within paragraphs (browsers are supposed to put air quotes around ```<p>``` but internet explorers don't so people usually avoid this).

### Abbreviations & Acronyms

```<abbr>```

A title attribute on the opening tag is used to specify the full term
(in HTML4 ```<acronym>``` element used to have it’s own to tag but since HTML5 ```<abbr>```been used for both).

### Citations & Definitions 

```<Cite>```

 when you are referring to a book,film or research paper ```<Cite>``` is used to indicated where the citation is from (browser render ```<Cite>``` in italic).

```<dfn>```

When you are explaining some new terminology in a document it is known as defining instance of it,
The ```<dfn>``` element is used to indicate the defining instance of a new term .

### author details 

```<address>```
It has a specific use ,it contains information about the web page author be it an address or email  

### changes to content

```<ins>```

```<del>```

```<ins>```elements shows the content that has been inserted into the document while ```<del>```shows the deleted content from it.

```<s>```

Indicating that something is outdated or not accurate or relevant ```<s>``` element will usually be displayed with a line through the center.

## intro into css

The key to understanding css is to imagine an invisible box around every HTML element and CSS allows you to individually create rules for each box to control the way it is presented.

How does css work

By associting rules with HTML elements these rules control the way the specific element is displayed, css made up of two parts: a selector and declaration 
Example :
```
P{
Font-family : arial;)
```
P: is the selector (indicating which element the rules will apply to )
And everything between { } is the declaration(indicating the rules that will be applied to the element)
Css declaration rules are made up by two parts: property and value.
The css rules usually appear in a separate document however sometimes may appear within the HTML page.

## basic javascript instructions summary

### statements 
A script is a series of instructions that the computer follows line by line and statements should end with a semicolon inciting when the step is over and the script should move on to the next step.
(JS is a case sensitive meaning HOUR and Hour are interrupted as two different things)

### comments

You can add comment to explain what you code does ,this will help you and someone reading the code to understand it faster 

There are two type of comments 

* single-line comments:used to brief description can be called by ( // )
* multi-line comment: used when the comment is over one line ( starts with /* and ends with */ everything between them then is commented)

Comments are not processed by the JS interpreter.
Good comments help you get back to your code weeks or months after.

 ### Variables

When the script have to temporarily store bit of information  it needs to do its job .it can store this data in a variable

How to we declare them variables are made up of to main part
variable key work and variable name 

Example:
 ```
var quantity;
```
Once we create a variable we can store information in it 

Example : 
```
quantity = 3;
```

### Data type

Common data type are
* numeric data type: are numbers 
* string data type : consists of letters and other characters
* boolean data type : can only have value of true or false 

We can use variables to store data types and change them.
Don’t forget when giving a name for a variable use a logical meaningful name.
### Array
Is a special type of variable, it doesn't just store one value but a list of values.

Arrays are good especially when you don’t know how many items the list will have 

Example :
```
Var colors = new Array(‘white’,
				       ‘Black’,
			           ‘custom’);
```
We called the array constructor then we put the values in the parentheses,
Arrays are store in the array as a numbered list starting from 0(not one) 
And we can access them by calling the array with the number

Example :
```
Item = colors[2]:
```
Item will have custom as it’s value 

### Operators 
 
They allow programmers to create a new single value from one or more value

 #### Arithmetic Operators 

JS contains the following mathematical operators which you can use with numbers
| Name  | character |
| ------------- | ------------- |
| Addition   | + |
| Subtraction   | - |
| Division   | / |
| Multiplication   | * |
| Increment    | ++ |
| Decrement    | -- |
| Modulus    | % |

And there is one string operator and its + symbol is used to join the string on either side of it 

## Decisions & loops

How to create scripts to handle different situations and run different code each situations

There are two component to a decision:

1- an expression is evaluated, which returns a value

2- a conditions; statement says what to do in given situation 

And we can do the by comparing operators and evaluating conditions 


| Name  | character |
| ------------- | ------------- |
| equal to   | == |
| not equal to    | != |
| strict equal to   | === |
| strict not equal to    | !== |
| greater than    | > |
| less than    | < |
| greater than or equal to    | >= |
| less than or equal to    | <= |

How can we compare using more than one comparison operator we use logical operators 

| Name  | character |
| ------------- | ------------- |
| logical AND   | && |
| logical OR    | \|\| |
| logical NOT   | ! |

### IF statements 

Checks if the condition is true or false 

Example :
```
if(score >= 50) {
congratulate();
}
```

### IF else statements 

It allow the operator to have 2 code blocks runs for each situation in our case using the example above 

Example :
```
if(score >= 50) {
congratulate();
} else {
encourage();
}
```
We used else to create a new solution for false condition 

### SWITCH statements 
Switch have a default case and different situational cases if none are met the default one will run and after each case we break; so the code stop from trying to check each case 
example :
```
Switch (level){
case ‘One’ :
Title =  ‘level 1’;
Break;
case two:
Title =  ‘level 2’;
Break;
case Three:
Title =  ‘level 3’;
Break;
default:
Title =  ‘test’;
break;
```