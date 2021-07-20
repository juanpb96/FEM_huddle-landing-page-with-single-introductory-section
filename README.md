# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). Frontend Mentor challenges help you improve your coding skills by building realistic projects! 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the page depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

Desktop view

![Solution preview](./design/Screenshot_Huddle-landing-page-with-single-introductory-section.png)

### Links

- Solution URL: [Click here](https://www.frontendmentor.io/solutions/mobilefirst-site-html5-scss-and-flexbox-UD8h5GUK0)
- Live Site URL: [See live site here](https://juanbonilla.me/FEM_huddle-landing-page-with-single-introductory-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS / SCSS custom properties
- Flexbox
- Icons - [IcoMoon](https://icomoon.io/)
- Mobile-first workflow

### What I learned

This is the first project in which I used a **mixin**, in my opinion, this is a really effective approach to create reusable block of code that are useful to reduce the lines of code written along the webpage. This time, I implement this structure to define a `display: flex` and get some specific values whenever is necessary. See the snippet below: 

```scss
@mixin flex($j-content: center, $a-items: center) {
    display: flex;
    justify-content: $j-content;
    align-items: $a-items;
}
```
For the example above, I decided to set default values in case any of them do not receive an specific value.

### Continued development

I want to continue implementing different features defined in the *Sass* guide. This time I used a **mixin** but for my next projects I will decide to increase the amount of *Sass* features that my webpage could have without force them to be there.

### Useful resources

- [Sass](https://sass-lang.com/guide) - This helped me when I wanted to use a block of code that could be reusable in my styles.

## Author

- Website - [juanbonilla.me](https://juanbonilla.me)
- Frontend Mentor - [@juanpb96](https://www.frontendmentor.io/profile/juanpb96)
- LinkedIn - [Juan Bonilla](https://www.linkedin.com/in/juan-pablo-bonilla-6b8730115/)
