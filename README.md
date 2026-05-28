# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
- [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](/screenshot.png)

### Links

- Solution URL: [Link](https://github.com/Mihasik556/Product-preview-card-component)
- Live Site URL: [Link](https://mihasik556.github.io/Product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- BEM Methodology
- Media Quaries
- CSS Variables

### What I learned

I`m really thankful for this project, because I've tried many new things in it. I practiced CSS Variables, continued wotking on Mobile-First Workflow, tried to make this project only using my eyes to see how sharp my 'CSS eye' is, met some problems when it came to media quaries.

For example, there is some code I`m proud of:

```css
/* VARIABLES */

/*--Colors--*/
:root {
    --BG-COLOR: hsl(30, 38%, 92%);
    --CARD-BG-COLOR: hsl(0, 0%, 100%);
    --BUTTON-TEXT-COLOR: hsl(0, 0%, 100%);
    --MAIN-TEXT-COLOR: hsl(228, 12%, 48%);
    --TITLE-COLOR: hsl(212, 21%, 14%);
    --MAIN-PRICE-COLOR: hsl(158, 36%, 37%);
    --BUTTON-BG-COLOR: hsl(158, 36%, 37%);
    --ACTIVE-BUTTON-BG-COLOR: hsl(158, 42%, 18%);
}

/*--Fonts--*/
:root {
    --BASIC-FONT: "Montserrat-M";
    --BASIC-FONT-BOLD: "Montserrat-B";
    --BASIC-FONT-SIZE: 0.875rem;
    --LABEL-FONT-SIZE: 0.75rem;
    --TITLE-FONT: "Fraunces-B";
    --TITLE-FONT-SIZE: 2.1rem;
    --MAIN-PRICE-FONT-SIZE: 2rem;
    --DELETED-PRICE-FONT-SIZE: 0.8rem;
}

/*--Border-Radius--*/
:root {
    --BORDER-RADIUS: 0.5rem;
}

/*--General-Styles--*/

.product__img {
    width: inherit;
    aspect-ratio: 1.025/1;
    background-image: url("../assets/images/image-product-mobile.jpg");
    background-size: contain;
    background-repeat: no-repeat;
    border-radius: var(--BORDER-RADIUS) var(--BORDER-RADIUS) 0 0;
}
```

### Continued development

I will definitely continue focusing on using variables, working through mobile-first workflow, making my projects more responsive and accessible

### AI Collaboration

I used Grok when stumbled into a problem when white space and words wrapping worked not how i needed them to. AI suggested a couple of ways how to fix it. Even though at the end I`ve solved the problem by myself, it was still very useful to hear some advices.

## Author

- Frontend Mentor - [@Mihasik556](https://www.frontendmentor.io/profile/Mihasik556)
- GitHub - [Mihail Gurgurov](https://github.com/Mihasik556)
