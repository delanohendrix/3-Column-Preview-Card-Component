# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- See hover states for interactive elements

### Screenshot

![Screenshot](/screenshot.png)

### Links

- Solution URL: [My Solution](https://www.frontendmentor.io/solutions/order-summary-component-g1SPiRrd4i)
- Live Site URL: [GitHub Pages](https://delanohendrix.github.io/3-Column-Preview-Card-Component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

In order to save time, I wanted to make the css as uniform as possible. By using psudeo elements I was able to change the background of each box, as well as the colors of the buttons without repeating myself too much.
An example of this:

```css
.card button {
  font-family: var(--f-paragraph);
  font-weight: 400;
  font-size: 15px;
  background-color: var(--bghbtn);
  border: 2px solid var(--transparent);
  padding: 15px 30px;
  border-radius: 30px;
}
.card:nth-child(1) button {
  color: var(--orange);
}
.card:nth-child(2) button {
  color: var(--cyan);
}
.card:nth-child(3) button {
  color: var(--dark-cyan);
}
.card button:hover {
  background-color: var(--transparent);
  border: 2px solid var(--bghbtn);
  color: var(--bghbtn);
}
```

### Useful resources

- [CSS Reference](https://cssreference.io/) - This site helped me by refreshing me on the usage of various css attributes and properties.

## Author

- Frontend Mentor - [@delanohendrix](https://www.frontendmentor.io/profile/delanohendrix)
