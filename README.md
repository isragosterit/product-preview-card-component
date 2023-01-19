# product-preview-card-component
# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](screenshots/desktop-size.PNG)
![](screenshots/mobile-size.PNG)

### Links

- Solution URL: (https://github.com/isragosterit/product-preview-card-component)
- Live Site URL: (https://isragosterit.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

I have learned using 'srcset' for changing pictures for different screen sizes.
``` 
<img src="image-product-desktop.jpg"
     srcset="image-product-mobile.jpg 600w,
             image-product-desktop.jpg 1200w"
     sizes="(max-width: 600px) 600px,
            1200px"
     alt="product">
``` 
### Useful resources

- [Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This resource is extremely helpful for Flexbox. Whenever I forget something, I always refer back to it.

## Author

- Frontend Mentor - [@isragosterit](https://www.frontendmentor.io/profile/isragosterit)
