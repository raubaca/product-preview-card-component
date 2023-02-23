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
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Product preview card component](./screenshot.png)

### Links

- Solution URL: [Frontend Mentor]()
- Live Site URL: [GitHub Pages]()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/)

### What I learned

By doing this project I was able to explore more about CSS Grid and learn about responsive images using the `<picture>` element.

```html
<picture>
  <!-- Images according media queries -->
  <source srcset="path-to-image/image-large.jpg" media="(min-width: 1440px)" />
  <source srcset="path-to-image/image-medium.jpg" media="(min-width: 768px)" />

  <!-- Default image -->
  <img src="path-to-image/image-default.jpg" alt="Default image alt" />
</picture>
```

### Useful resources

- [mdn - Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)
- [A Guide to the Responsive Images Syntax in HTML](https://css-tricks.com/a-guide-to-the-responsive-images-syntax-in-html/)
- [web.dev - Responsive Images](https://web.dev/learn/design/responsive-images/)

## Author

- Frontend Mentor - [@raubaca](https://www.frontendmentor.io/profile/raubaca)
- Twitter - [@raubaca](https://www.twitter.com/raubaca)
- LinkedIn - [Raúl Barrera Castiblanco](https://www.linkedin.com/in/raubaca/)
- CodePen - [Raúl Barrera Castiblanco](https://codepen.io/raubaca)
