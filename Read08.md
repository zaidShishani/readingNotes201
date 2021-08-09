# Chapter 15: Layout
revisiting Layout from Read04

Will be discussing the different ways to designe screens for other mediums 
* Explore different ways to position e ●● lements using normal flow, relative positioning, absolute positioning and floats.
* Discover how various devices have different screen sizes
and resolution, and how this affects the design process.
* Learn the difference between fixed width and liquid layouts, and how they are created.
* Find out how designers use grids to make their page
designs look more professional.

## key concepts in positioning elements
CSS trasts HTML elements as boxes the boxes will be either block- level box or inline box 

* block-level elements starts on a new line.
* inline elements flow in between surrounding text

### Containing Elements
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element

## Controlling the position of elements
CSS has the following ```positioning schemes``` that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.
1. Normal flow
2. Relative Positioning
3. Absolute positioning
To indicate where a box should be positioned, you may also need to use ```box offset``` properties to tell the browser how far from the top or bottom and left or right it should be placed.

## Screen Size 
Each user has a different size screen that will show different sizes of information. Our design has to keep that in mind.

## Screen Resolution
Refers to the number of dots per inch some have high other have low desktops can even offer options 

## Page size 
Designer try to create pages around 960-100 pixels since screen size and display resolution vary so much 

## Fixed Width Layouts
Fixed width layout designs do not change size as the user increases or decreases the size of their browser window.
| Advantages  | Disadvantages |
| ------------- | ------------- |
| Pixel values are accurate at controlling size and positioning of elements.  | You can end up with big gaps around the edge of a page. |
| The designer has far greater control over the appearance and position of items on the page than with liquid layouts.  | If the user's screen is a much higher resolution than the designer's screen, the page can look smaller and text can be harder to read. |
| You can control the lengths of lines of text regardless of the size of the user's window.  | If a user increases font sizes, text might not fit into the allotted spaces. |
| The size of an image will always remain the same relative to the rest of the page.  | The design works best on devices that have a site or resolution similar to that of desktop or laptop computers. |
|   | The page will often take up more vertical space than a liquid layout with the same content. |

## Liquid Layouts
Liquid layout designs stretch and contract as the user  ncreases or decreases the size of their browser window.

| Advantages  | Disadvantages |
| ------------- | ------------- |
| Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.  | If you do not control the width of sections of the page then the design can look very different than you intended, with unexpected gaps around certain elements or items squashed together. |
| If the user has a small window, the page can contract to fit it without the user having to scroll to the side.  | If the user has a wide window, lines of text can become very long, which makes them harder to read. |
| The design is tolerant of users setting font sizes larger than the designer intended (because the page can stretch).  | If the user has a very narrow window, words may be squashed and you can end up with few words on each line. |
|   | If a fixed width item (such as an image) is in a box that is too small to hold it (because the user has made the window smaller) the image can overflow over the text. |

## CSS Frameworks
CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, tyling forms, creating printer-friendly versions of pages and so on. You