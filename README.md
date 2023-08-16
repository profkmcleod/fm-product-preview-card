# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./mobile-view.PNG)
![](./desktop-view.PNG)

### Links

- [Solution URL](https://www.frontendmentor.io/solutions/css-variables-flexbox-3NUcHhxUHz)
- [Live Site URL](https://profkmcleod.github.io/fm-product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

I loved using the picture element!

To see how you can add code snippets, see below:

```html
<div class="product-image">
      <picture>
        <source srcset="images/image-product-mobile.jpg" alt="mobile product image">
        <source media="(min-width: 1024px)" srcset="images/image-product-desktop.jpg" alt="desktop product image">
        <img src="images/image-product-mobile.jpg" alt="perfume">
      </picture> 
    </div>
```

### Continued development

Becoming more familiar with working with images is definitely needed.

### Useful resources

- [Display Different Imgages based on device width](https://www.youtube.com/watch?v=nHB-3WJTfSg) - I really liked using the picture element in lieu of relying soley on media queries.

## Author

- Frontend Mentor - [@profkmcleod](https://www.frontendmentor.io/profile/profkmcleod)
