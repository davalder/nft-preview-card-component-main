# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

NFT information card design, using CSS and BEM methodology, responsive design, applying mobile first with media query for desktop PC, in addition to adding actions with user interactivity.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- BEM
- Flexbox
- Mobile-first workflow

### What I learned

Using Pseudo classes in this project was one of the main insights entrenched, with HTML node nesting, for example:

```html
<div class="container__imagen">
        <div class="container__imagen--hover"></div>
        <span></span>
      </div>
```
```css
.container__imagen:hover span {
    display: inline-block;
    position: absolute;
    z-index: 2;
    width: 4.6rem;
    height: 3.1rem;
    background-image: url('../assets/icons/icon-view.svg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
```

### Continued development

The steps to follow are to strengthen my frontend skills using CSS and JS pre-processors, with which I will seek to learn the handling of REACT.JS

## Author

- Frontend Mentor - [@davalder](https://www.frontendmentor.io/profile/davalder)
- GitHub - [@davalder](https://github.com/davalder)

## Acknowledgments

I thank Diego De Granada for his HTML and CSS classes at the web development school in Platzi.