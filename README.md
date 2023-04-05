# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- Build out the project to the designs provided

### Screenshot

![mobile-view](images/mobile-view.png)
![desktop-view](images/desktop-view.png)

### Links

- [View solution on Frontend Mentor](https://your-solution-url.com)
- [View live site](https://your-live-site-url.com)

## My process

### Built with

- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- BEM

### What I learned

How to use multiple background images together and positioning them.

``` css
body {
    background-color: var(--dark-cyan);
    background-image: url("images/bg-pattern-top.svg"),
        url("images/bg-pattern-bottom.svg");
    background-repeat: no-repeat;
    background-position: right 180px bottom 300px, left 170px top 280px;

}
```

- Multiple background images can be defined in a single declaration separated by a commmas. 

``` css
background-image: url("images/bg-pattern-top.svg"), url("images/bg-pattern-bottom.svg");
        
```

- Always define a background-color even if the background image covers the whole viewport or is opaque. Incase the image can't be loaded, the background color will be used as a fallback.

- A background color is rendered beneath a background image.

- In the case of `background-repeat` property, the `no-repeat` value does not have to be specified for each image used and separated by a comma as such: `background-repeat: no-repeat, no-repeat`;. One `no-repeat` value will affect all available images.

### Useful resources

- [Using multiple images](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Using_multiple_backgrounds)
- [Background position](https://developer.mozilla.org/en-US/docs/Web/CSS/background-position)
- [Background image](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image)

## Author

- Frontend Mentor - [@dennisthekin](https://www.frontendmentor.io/profile/dennisthekin)