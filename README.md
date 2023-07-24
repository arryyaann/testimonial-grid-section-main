# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size



### Links

- Live Site URL: [Add live site URL here](https://arryyaann.github.io/testimonial-grid-section-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

During the project I learnt the basics of CSS Grid and how to properly use the dev tools.



```css
@media (min-width: 63em) {
  .grid-col-span-2 {
    grid-column: span 2;
  }

  .testimonial-grid {
    grid-template-columns: repeat(4, 1fr);
  }

  .testimonial:last-child {
    grid-column: 4;
    grid-row: 1 / span 2;
  }
}
```



## Author

- Website - [Aryan Sarangal](https://arryyaann.github.io/testimonial-grid-section-main/)
- Frontend Mentor - [@arryyaann](https://www.frontendmentor.io/profile/arryyaann)



## Acknowledgments

Heavly inspired by the following yotube video - (https://www.youtube.com/watch?v=rg7Fvvl3taU)
