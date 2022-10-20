# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./design/capture_desktop.png)


![](./design/capture_mobile.png)


![](./design/capture_mobile_menu.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Usually I use tailwind CSS. For this vanilla CSS project, I was able to understand a little better how grids and responsive work, especially for font sizes (with clamp() ).

### Continued development

I still have problems adapting the design to mobile for loading images. The srcset property seems not to work in my current usage.

### Useful resources

- [CSS Clamp](https://www.smashingmagazine.com/2022/01/modern-fluid-typography-css-clamp/) - This helped me for responsive font without change font-size value through multiple breakpoints.

## Author

- Frontend Mentor - [@Fabustis](https://www.frontendmentor.io/profile/Fabustis)

## Acknowledgments

I mean mobile first is a better approche and avoid some useless lines (with default value in columns with Grid for exemple, like "grid-template-columns: auto;")
