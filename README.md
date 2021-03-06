# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). 

- Date: 25 March 2022

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Finished Porduct](#finished-product)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Issue Found](#issue)
- [Author](#author)
- [Date](#date)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Finished Product

- Desktop Version: [Screenshot 1](./finished/desktop%20version.png)
- Mobile Version: [Screenshot 2](./finished/mobile%20version.png)
- Hover effect is available.


### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/nft-preview-card-component-challenge-Bkf7GS9G9)
- Live Site URL: [Live](https://ethenpage.github.io/nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

- [Learn 1](./finished/learn%20one.png) 
- Hover within two image.
- Use of Pseudo-elements (::before, ::after).
- Use of absolute and relative position.

### Continued development

- Hover Animation.

## Issue

- `<hr>` tag with color is not working in chrome but in firefox. Use the following instead of `<hr>`:

```html
<div class="line"></div>
```
```css
.line{
    background-color: var(--line);
    padding: 1px 0;
}
```

## Author

- Name - Mirza Monirul Alam
- Frontend Mentor - [@EthenPage](https://www.frontendmentor.io/profile/EthenPage)

## Date

25 March 2022