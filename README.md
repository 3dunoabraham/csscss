# CSSCSS
#### Utility-first CSS framework.

## Installation
You can install CSSCSS using npm by running the following command:
```bash
npm install csscss
```
Alternatively, you can include the CSS file directly in your HTML using the following link:
```html
<link rel="stylesheet" href="https://unpkg.com/csscss@latest/index.css">
```



## Features
CSSCSS includes a wide range of utility classes that are organized into different categories based on their purpose. Here's an overview of what you can expect:
- A responsive grid system based on the Flexbox layout model.
- Predefined classes for adding margins and paddings to elements.
- A set of color classes for quickly applying background and text colors.
- Several text styles for headings, paragraphs, and links.
- Various button styles for creating different types of buttons.
- A collection of utility classes for commonly used CSS properties.
- Several animation classes for adding animations to elements, such as fading in/out, scaling, and rotating.
- Overall, the CSSCSS package provides a comprehensive set of styles that can help simplify and speed up the process of building a website or web application.




## Position
Classes for controlling the positioning of elements on the page

Some examples of the classes and what they do:
* Position: "pos-rel" sets the position of an element to relative.
  * variations:
    * ["rel","abs","fix","fixed"]
* Edge Positioning: "top-0" and "top-25p" sets the top position of an element to 0 and 25% respectively.
  * types: ("top-","left-","right-","bottom-")
  * variations:
    * ["0","25p","50p","75p"]
* Size: "w-50" and "w-10" sets the width of an element to 50% and 10% respectively.
  * types: ("w-","h-") for width and height
  * percentage variations ("w-50" or "w-10"):
    * [10,20,25,30,33,40,50, ... ,90,100]
  * viewport percentage variations ("w-100vw" or "h-100vh"):
    * [100]
  * maximum viewport percentage variations (has "max" in the middle, ie "w-max-80vw" or "h-max-100vh"):
    * subtypes (ends with "vw" or "vh"):
    * [80,100]
  * pixel variations (ends in "px", ie "h-50px" or "w-100px"):
    * [50,80,100,120,150,200,250,220,300,400,450,500,600,650,700,1080]
  * maximum pixel variations (has "max" in the middle, ie "w-max-250px" or "w-max-200px"):
    * [50,80,100,120,150,200,250,220,300,400,450,500,600,650,700,1080]
* Z Index: "z-300" sets the z-index of an element to 300
  * types: ("z-300" or "z--300") for positive 300 or negative 300 z index
  * variations ("z-300" or "z--999"):
    * [1,2,3,5,10,50,100,200,300,400,500,600,700,800,999,1000,1001]

## Width & Height
* size of elements on the page, such as .w-50, .w-100, and .w-100vw.
* height of elements on the page, such as .h-100, .h-100-vh, and .h-50vh.
## PADDING & MARGIN
## STRUCTURE
* display property of elements, such as .hidden, .none, .block, and .flex.
* flexbox layout of elements, such as .flex-center, .flex-row, and .flex-column.
* alignment of flexbox elements, such as .flex-align-start, .flex-align-end, and .flex-align-center.
* justification of flexbox elements, such as .flex-justify-start, .flex-justify-end, and .flex-justify-center.
* self-alignment of flexbox elements, such as .flex-self-align-start, .flex-self-align-end, and .flex-self-align-center.
## Background
* background of elements, such as .bg-red, .bg-blue, and .bg-green.
* shape of elements, such as .rounded, .rounded-lg, and .circle.
* border of elements, such as .border, .border-l-1, and .border-b-5.
## BORDER
## Text
* text properties of elements, such as .tx-lg, .tx-center, and .tx-bold.
* spacing of text, such as .letter-s-2 and .word-s-3.
* decoration of text, such as .nodeco, .nowrap, and .strikethrough.
## CURSOR
## Opacity
* opacity of elements, such as .opacity-50 and .opacity-hover-25.
## Filter
## Media Query
* the viewport size, such as .sm, .md, and .lg.
* a range of viewport sizes, such as .md-xl.
* a combination of viewport sizes, such as .sm-md-only.
* Advanced complex combinations of viewport sizes.
## Animation
* Classes for adding animations to elements, such as .hover-hover, .spin-spin, and .shake-shake.
