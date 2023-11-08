# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

The challenge was to build a responsive layout to show a single price grid component and get the design to look as close as possible to the provided design images.

### Screenshot

![Desktop single price grid screenshot](./images/single-price-grid-desktop-screenshot.jpg)
<img src="./images/single-price-grid-mobile-screenshot.jpg" height="350px" />

### Links

- Solution URL: [https://github.com/VTickner/frontend-mentor-single-price-grid-component](https://github.com/VTickner/frontend-mentor-single-price-grid-component)
- Live Site URL: [https://vtickner.github.io/frontend-mentor-single-price-grid-component/](https://vtickner.github.io/frontend-mentor-single-price-grid-component/)

## My process

- Created semantic HTML first
- Created CSS selectors to:
  - create custom variables to contain the various colours, font sizes font weights used in the design
  - used a CSS reset
  - layout the design using Grid and Flexbox
  - style the various elements
  - added in `:focus` styling for accessibility purposes
  - create a different width layout for mobile version turning the component into a single grid column

### Built with

- Semantic HTML markup
- CSS custom properties
- Grid
- Flexbox
- Desktop-first workflow (responsive design)
- Google Font

### What I learned

I didn't learn anything new on this project, but did gain some extra practice with using a grid layout. From a [blog post](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) I read, using the 62.5% trick isn't ideal, so I redid my CSS to remove that particular CSS trick and use CSS variables to hold the values of appropriate font sizes in rems.

### Continued development

Create more designs that have a more complicated grid layout, to gain extra practice using CSS grid.

### Useful resources

- [Google Fonts](https://fonts.google.com/) - The font used in this design was [Karla](https://fonts.google.com/specimen/Karla).
- [Josh W Comeau Blog](https://www.joshwcomeau.com/css/surprising-truth-about-pixels-and-accessibility/) - A blog post discussing accessibility regarding px, em, rem and the 62.5% trick.

## Author

- Frontend Mentor - [@VTickner](https://www.frontendmentor.io/profile/VTickner)
