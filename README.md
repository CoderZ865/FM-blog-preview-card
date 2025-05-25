# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![Screenshot](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I used two levels of variables, nesting of CSS selectors and combinators, and a variable to store more than one value for shorthand properties. I also implemented responsive design using `clamp` instead of media queries. Initially, I used `100%` for the preferred value, but it didn't work as expected because it was using 16px. Then, I tried `vw`, which worked as intended.

```css
.proud-of-this-css {
    --body:
     var(--fw-medium)
     clamp(12px,3vw,var(--fs-body))/
     var(--lh-150)
     var(--font-body);

    width: clamp(327px, 100%, 384px);
}
```

### Continued development

I want to learn more about Grid and Flexbox layouts to improve my skills in these areas.


## Author

- Frontend Mentor - [@CoderZ865](https://www.frontendmentor.io/profile/CoderZ865)

