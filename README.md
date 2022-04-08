# Frontend Mentor - Single price grid component

## Welcome! 👋

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![Design preview for the Single price grid component coding challenge](./design/desktop-design.png)

![Design preview for the Single price grid component mobile view](./design/mobile-design.png).

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- CSS Media Queries

### What I learned

I learned the handling of the CSS Grid component and the use of the grid-template-areas property. Use semantic HTML 5 tags, the final layout adjusts based on the screen size of the display device.
Here are some CSS code snippets applied in the solution:

```css
.main-container {
  display: grid;
  grid-template-areas: 
    "section1 section1"
    "section2 section3";
}

.section1 {
  grid-area: section1;
}
```
## Author

- Frontend Mentor - [@franciscojoel97](https://www.frontendmentor.io/profile/franciscojoel97)
- Twitter - [@FranciscoJoelC4](https://twitter.com/FranciscoJoelC4)
