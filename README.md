# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

I just finished the Responsive Web Design course on freeCodeCamp and wanted to exercise.

This is actually my first challenge here.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/screenshot.jpg)

### Links

- My Solution: [CodePen](https://codepen.io/ivelinsm/pen/WNOXVPB)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I played A LOT with paddings and margins to get it look like the jpg. 
But... what really made this challenge tough and troublesome were the rounded corners.

Took me maybe an hour to find a solution. 

I tried with border-collapse, then the perspective property. I played with the parent container, then decided to add one container more. And finally saw a comment on stackoverflow... and it worked. Overflow FFS!

```css
.proud-of-this-css {
  overflow: hidden;
}
```

### Useful resources

- [Stackoverflow comment that saved the day](hhttps://stackoverflow.com/questions/10995294/border-radius-not-working#comment87137853_44334424) - This is the comment that helped me with the rounded corners.
- [freeCodeCamp](https://www.freecodecamp.org) - This is where I have learned all the basic stuff. I completed the Responsive Web Design Course just a few days ago.

## Author

- freeCodeCamp - [Account](https://www.freecodecamp.org/fcc927d30f9)
- Frontend Mentor - [@ivelinsm](https://www.frontendmentor.io/profile/ivelinsm)
- Github - [@ivelinsm](https://github.com/ivelinsm)

## Acknowledgments

A big thank you to Frontend Mentor about the cool challenge. 
