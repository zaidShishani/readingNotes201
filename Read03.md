# Lists
There are 3 types of lists 

Ordered lists
Unordered lists
Definition lists

## Ordered lists
This lists gives an ordered number to each item on the lists .

To create an ordered list we call the tag```<ol>``` and each items will be placed between ```<li>``` and ```</li>```.

## Unordered lists
This list gives a bullet point for each item on the list.

To create an unordered list we call the tag```<ul>``` and each items will be placed between ```<li>``` and ```</li>``` the same as ordered but instead of ```<ol>```we used  ```<ul>```.

## Definition lists
This list is made up of dentists along with a set of deception for it.

To create an ordered list we call the tag```<dl>``` and since it consists of pairs of terms and their definitions we use ```<dt>``` for the term and ```<dd>``` for the description.

## Nested Lists

We can put another list in our list inside the ```<ul>``` tag  to create a nested list.

# Boxes
CSS allows us to control invisible boxes that presents our content 

By allowing us to
* control the dimension of the boxes
* create borders around the boxes
* set margins padding for the boxes
* show and hide the boxes


## Box dimensions 
By default the box is just big enough to hold it’s content but we can change it using width and height. We can use pixels to determine the size or relative percentages or ems based on the size of the content.
## Limiting width
Using min-width, max width
We can shrink or expand to fit the size of the user's screen where min-width is the smallest it can get and max-width is as big as it can get 

## Limiting height
Same as width we may need to max or min to fit with the user min for the smallest it can get and max for the biggest it can get 

## Overflowing content
The overflow tag deals with if the content is bigger than the box it either hide the extra content  or make it a scroll to scroll expanded beyond what is shown

## Border, Margin & Padding

Each box have the properties that can be adjusted
* Border : every box has a border even if it is not visible the border separates the edge of the box from another.
* Margin :you can think about it as a smaller box inside the box where you can create the gap between the borders of two adjacent boxes.
* Padding:is the space between the boxand any content in it increasing the padding makes it more readable. 

### White space & Vertical margin

The padding and margin are very helpful to add space between the boxes on the page

### Border Width

border-width: Is the rule that govern the width of a border

### Border Style

Border-style: IS the style of the border it comes in different properties 
* solid: a solid line
* dotted: a series of dots 
* dashed: series of short lines
* double: two solid lines
* groove: lines carved into the page
* ridge: appears to stick out of the page
* inset: appears embedded into the page
* outset: appears like its coming out of the screen
* hidden / none: no border is shown

### Border color

Border-color : gives the border color.

### Centering content

To center a box in the middle of the page you can set the left-margin and right-margin to auto
Or center it inside the elements that inside of it 

### display

Allows you to give the inline elements different values like:

* inline :makes the block act like inline element, 
* block: let the inline elements act like a block-level element ,
* inline-block: allows the block-level element to flow like an inline element while still having the block-level elements features.
* none:hides the elements from the page.

### Hiding boxes

Allows us to hide the boxes leaving the space where the element would have been.

* hidden: hides the element
* visible : shows the element (it’s better to use the display property with value itsdead of none)

### Border images 

Applies an image to the border of any box it takes as a background.

### Border shadow

Give the boxes a drop shadow effect around it, it can be either a Horizontal offset, vertical offset, blur distance or spread of shadow.

### Border radius

CSS3 allows us to create rounded corners on our boxes. The value of the radius is indicated in pixels it helps us create more complex shapes.

##Arrays

Arrays are special types of variables that store a list of values best used when you are working on a list or set of values that relate to each other.

### Creating Array

To create a array we assign a values inside  variable by putting them between pair of square brackets and each value is separated by a comma 
example:
```
colors= ['white',
        'Black',
        'Custom'];
```

### values in array

Values in array are saved in numbered list starting from 0
So if we want to access to black we by calling the array and calling for 1
Example:
````
colors[2] ;
````

# Swtich

Switch value is the if statement but contains multiple cases. It is used when the question isn’t just true or false but has multiple answers.

## Truthy & Falsy values

Due type coercion every value in js can be treated as true or false
Here's A list of some of truthy values when var value = :
* true; traditional boolean true
* 1; number other than zero is true 
* ‘carrot’; cuz it is a string
* 10/5; cuz it is number calculation
* ‘true’; cuz it is a string
* ‘0’; cuz it is a string
* ‘false’; cuz it is a string

Here's A list of some of falsy values when var value = :
* false; traditional boolean false
* 0; number zero is falsy
* ‘ ’; NaN is falsy
* 10/’score’ ; cuz empty value
* ; a variable with no value assigned it to is falsy 
# Loops

Loops check a condition if it is true it will redo the code block til the condition is false 
Types of loops 

* for loop
* while loop
* do while loop

## for loop
For loops are often used to loop through an array by going the the array using array.length and stopping when it has been thought it all.
Syntax example  :
```
Var array = [21,22,23,24]
Var Count =0;
for( i = 0 ; i < array.length ; i++) {
	Count = i+1;
} 
```
## while loop
It keeps on looping till the condition is met
Syntax example  :
```
Var pizzaSlice = 8;

While (pizzaSlice != 0 ){
	Eat a pizza
	pizzaSlice - -; 
}
```

## do while loop
The key difference between do while and while loop is that do while will run the block of code then check the condition while while loop check the condition then does the block of code.
Syntax example  :
```
Var count = ‘ ’;
Var i = 0;

do (
i=i+1
count = count +1
)
```