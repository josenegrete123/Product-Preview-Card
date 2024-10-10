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

![](./Product-Preview-Card%20Solution.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://josenegrete123.github.io/Product-Preview-Card/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Learnt how to better utilize the @media query.

```css
@media only screen and (min-width: 45em) {
    .img {
        content: url('images/image-product-desktop.jpg');
        border-radius: 0.75em 0 0 0.75em;
    }
    .container {
        display: flex;
        justify-content: center;
        height: 28em;
    }

    .row {
        display: flex;
        flex-direction: column;
        justify-content: space-evenly;
        border-radius: 0 0.75em 0.75em 0;
        width: 35%;
    }
}

@media only screen and (min-width: 90em) {
    .row {
        width: 20%;
    }
}
```

### Continued development

Work more on writing better HTML and figure out better ways to write responsive CSS.

### Useful resources

- [Basis of the CSS](https://piccalil.li/blog/a-more-modern-css-reset/) - Used this to set the base of the CSS file for all elements.

## Author

- Website - [Jose Negrete](https://github.com/josenegrete123)
- Frontend Mentor - [@josenegrete123](https://www.frontendmentor.io/profile/josenegrete123)