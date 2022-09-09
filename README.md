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
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Interact with the mobile menu button and see navigation throgh that

### Screenshot

![](/images/screenshots/sunnyside.png)
![](/images/screenshots/sunnyside-2.png)

### Links

- Live Site URL: [Sunnyside Agency Landing Page](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Using `::before` to add the underline effects in the links
```css
.content > .link::before {
    content: '';
    position: absolute;
    bottom: -3px;
    width: calc(100% + 16px);
    left: -8px;
    height: 10px;
    background-color: var(--color);
    z-index: -1;
    border-radius: 10px;
    opacity: 0.3;
    transition: opacity 200ms ease-out;
}

.content > .link:hover::before {
    opacity: 0.7;
}
```

### Continued development
I want to use more Grid CSS in my development, sometimes Grid is way more efficient than Flexbox.
I experimented with CUBE CSS in this project. But it didn't work so well, so I mostly sticked with BEM methodology

## Author
- Frontend Mentor - [@wellington-damasio](https://www.frontendmentor.io/profile/wellington-damasio)