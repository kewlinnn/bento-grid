# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Bento grid solution](#frontend-mentor---bento-grid-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
      - [Desktop View](#desktop-view)
      - [Mobile View](#mobile-view)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot
#### Desktop View
<img src="./design/desktop-screenshot.png" alt="Desktop Screenshot" width="800px">

#### Mobile View
<img src="./design/mobile-screenshot.png" alt="Mobile Screenshot" width="375px">



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned
Working on this project reinforced my understanding of CSS Grid and its versatility in creating complex layouts. Here's an example of a key takeaway:

```CSS
.grid-container {
  display: grid;
  grid-template-areas:
    "A B B C"
    "A D E C"
    "F D E C"
    "F G H H";
  grid-template-columns: 20% 30% 30% 20%;
  gap: 20px;
  grid-template-rows: auto;
}
```
This structure allowed for a dynamic, responsive grid layout that adapts to various screen sizes.



### Useful resources
- [MDN Web Docs - CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout) - A comprehensive guide to mastering CSS Grid.
