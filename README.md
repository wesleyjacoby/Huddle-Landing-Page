# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0). 

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

- View the optimal layout for the page depending on their device's screen size.
- See hover states for all interactive elements on the page.

### Screenshot

![](./images/huddle-landing-page-desktop.png)
![](./images/huddle-landing-page-mobile.png)

### Links

- Solution URL: [GitHub](https://github.com/wesleyjacoby/Huddle-Landing-Page)
- Live Site URL: [GitHub Pages](https://wesleyjacoby.github.io/Huddle-Landing-Page/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Font Awesome
- Figma

### What I learned

I struggled with getting the social media icons centered within the border. By using Firefox dev tools, I saw that there was a default display setting for the class `.fa-brands`:

```css
display: var(--fa-display,inline-block);
```
I then figured out that I needed to up the specificity to override that code with my own:
```css
i.fa-brands {
    display: flex;
    }
```

I unfortunately still find myself struggling with the general layout of the webpage though.

### Continued Development

I still need to keep practicing and hopefully the layout side of things will get easier.

## Author

- Frontend Mentor - [@wesleyjacoby](https://www.frontendmentor.io/profile/wesleyjacoby)