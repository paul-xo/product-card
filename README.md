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
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshots/Desktop%20view.png)
![](./screenshots/Mobile%20view.png)

### Links

- Solution URL: (https://www.frontendmentor.io/solutions/product-preview-card-component-HMvKAkMp4o)
- Live Site URL: (https://product-cardd.pages.dev/)

## My process

I created a class called container and i put all the images and texts in it. I divided the container into 50% each for the image and texts while working with the desktop view and i gave it a display of flex. For the mobile view, i divided the container class into two and i gave the image a width of 100% and an height of 40%. I gave the texts a width of 100% too!

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I learnt that i should always use 'rem' for my margins and paddings. It'll make the website more responsive!

To see how you can add code snippets, see below:

```html
<div class="pricings-2">
  <h1>$149.99</h1>
  <p>$169.99</p>
</div>
<div class="pricings">
  <h1>$149.99</h1>
  <p>$169.99</p>
</div>
```

```css
.pricings {
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 2rem;
}
.pricings-2 {
  display: none;
}
.pricings-2 {
  display: block;
  display: flex;
  align-items: center;
  gap: 1rem;
  margin-bottom: 1.5rem;
}
```

### Continued development

- All HTML and CSS challenges on Frontend Mentor
- Portfolio

## Author

- Frontend Mentor - [@paul-xo](https://www.frontendmentor.io/profile/paul-xo)
- GitHub - [@paul-xo](https://www.github.com/paul-xo)
