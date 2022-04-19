# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](/design/screenshot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this challenge I learned about the CSS property "mix-blend-mode", in order to achieve the desired effect in the image 😃.

```css
.card__img-container {
  position: relative;
  background-color: var(--clr-violet);
}

.card__img {
  mix-blend-mode: multiply;
}

.card__overlay {
  position: absolute;
  content: "";
  width: 100%;
  height: 100%;
  background-color: var(--clr-violet);
  opacity: 0.25;
  top: 0;
  left: 0;
}
```

## Author

- Frontend Mentor - [@IsaiasVillegas](https://www.frontendmentor.io/profile/IsaiasVillegas)
