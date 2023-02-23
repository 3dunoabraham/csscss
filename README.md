# CSSCSS
#### An easy and consistent utility-first CSS framework.

```bash
npm install
```

The classes are organized into different categories based on their purpose.

POSITION: classes for controlling the positioning of elements on the page
WIDTH & HEIGHT: classes for controlling the size of elements on the page
Some examples of the classes and what they do:

.pos-rel: sets the position of an element to relative
.pos-abs: sets the position of an element to absolute
.pos-fixed: sets the position of an element to fixed
.top-0: sets the top position of an element to 0
.left-0: sets the left position of an element to 0
.right-0: sets the right position of an element to 0
.bottom-0: sets the bottom position of an element to 0
.w-50: sets the width of an element to 50%
.w-100: sets the width of an element to 100%
.w-100vw: sets the width of an element to 100% of the viewport width
.w-50px: sets the width of an element to 50 pixels
.z-1: sets the z-index of an element to 1
.z-10: sets the z-index of an element to 10
.z--1: sets the z-index of an element to -1
.z--10: sets the z-index of an element to -10
These classes can be used to create responsive layouts and apply styles to different elements on the page.
Display
hidden | none | block
clickable | nopointer , noclick | nocursor
​
## Display
flex | flex-center | flex-row | flex-column
flex-wrap | flex-row-r | flex-column-r
flex-between | flex-around | flex-1
flex-align-start | flex-align-end | flex-align-center
flex-justify-start | flex-justify-end | flex-justify-center
flex-self-align-start | flex-self-align-end | flex-self-align-center


# STRUCTURE
## Background
Shape
noborder
border-l-? | border-r-? | border-t-? | border-b-? | (5,10,15,25,50,100p)
## Text
tx-xxxl | tx-xxl | tx-xl | tx-lg | tx-md | tx-sm | tx-xs
tx-center | tx-end | tx-right | tx-start | tx-left
​
tx-ls-s-? | letter-s-? | (1-5,10,15,25)
word-s-? | (1-5,10,15,25)
​
# UPDATE
tx-bold | tx-italic
nodeco | nowrap | linethrough | strikethrough
Space
w-100 | w-100-vw | v-50 | w-50vw
h-100 | h-100-vh | h-50 | h-50vh
ma-? | ml-? | mr-? | mt-? | mb-? | (0-8,100,200)
pa-? | pl-? | pr-? | pt-? | pb-? | (0-8,100,200)
## Animation
hover-hover | hover-nhover | spin-spin | spin-nback
shake-shake | shake-nback
Filter
opacity-? | opacity-hover-? | (5,10,25,50,75)
## Media Query
Basic
Basic Range
Basic Combo
Advanced Range Combo
