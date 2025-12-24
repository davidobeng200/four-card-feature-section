# Frontend Mentor - Four card feature section solution

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

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

The challenge was to build a responsive four-card feature section that adapts well to both mobile and desktop screen sizes. The layout needed proper alignment, spacing, and visual hierarchy while closely matching the provided design.

### Screenshot

![](./screenshots.png)



### Links

- Solution URL: [GitHub Repository](https://github.com/davidobeng200/four-card-feature-section.git)
- Live Site URL: [GitHub Pages](https://davidobeng200.github.io/four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow



### What I learned


- How to position elements inside a container using position: relative and position: absolute

- How to use box-shadow to improve UI depth

- How to make layouts responsive using media queries

- Why min-height is better than height for responsive layouts

# Using Position: Relatiive and Position: Absolute
```css
.cards {
  position: relative;
}

.icons {
  position: absolute;
  bottom: 20px;
  right: 20px;
}
```
# Using Box Shadow
```css
.cards {
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
}
```
# Using Media Queries
```css
@media (max-width: 768px) {
  .cards-container {
    flex-direction: column;
    align-items: center;
  }
}
```

### Continued development
In future projects, I want to:

- Improve typography responsiveness using clamp()

- Practice CSS Grid for more complex layouts

- Focus more on accessibility and semantic structure

### Useful resources

- [W3schools](https://www.w3schools.com/css/default.asp) - Helped me understand basic CSS concepts such as positioning, box-shadow, and media queries.
 

## Author

- Website - [DAVID OBENG ADJEI](https://davidobeng200.github.io/four-card-feature-section/)
- Frontend Mentor - [@davidobeng200](https://www.frontendmentor.io/profile/davidobeng200)



