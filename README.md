# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [How I did it](#how-i-did-it)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![](./design/desktop-design.jpg)

### Links

- Solution URL: [GitHub repository](https://github.com/AyulaBoyilo/FMintroSectionHuddle/)
- Live Site URL: [GitHub Pages](https://ayulaboyilo.github.io/FMintroSectionHuddle/)

## My process

### Built with

- Semantic HTML5 markup
- SCSS and CSS3
- Flexbox

### How I did it

Instead of once again fiddling with individual sizes of the social icons for the desktop media query, I just scaled up the entire thing.
Added an elastic, view-width dependant margin-left for the text content column of the banner to balance out the relative lack of right hand content on the larger screens.

```scss
a {
  transform: scale(1.2, 1.2);
}
```

```scss
.content {
  margin-left: 7vw;
}
```

## Author

- Ayula Boyilo
