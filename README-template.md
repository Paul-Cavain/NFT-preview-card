# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: https://github.com/Paul-Cavain/NFT-preview-card
- Live Site URL: https://nft-preview-card-mauve-seven.vercel.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

1.  HTML semantic way of using html tags

```html
<div class="time-interval">
  <div class="ethereum"><img src="./images/icon-ethereum.svg" />0.041ETH</div>
  <div class="clock"><img src="./images/icon-clock.svg" />3 days left</div>
</div>
```

```css
body,
html {
  background-color: hsl(217, 54%, 11%);
  height: 100vh;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: "Outfit", sans-serif;
}
.card {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: start;
  padding-top: 18px;
  padding: 18px;
  width: 350px;
  border-radius: 10px;
  background-color: hsl(216, 50%, 16%);
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
```

### Continued development

1. FlexBox
2. html tags
3. Font-Fanily

## Author

- Website - https://nkelegome-paulcavains-projects.vercel.app/
- Frontend Mentor - [@Paul-Cavain](https://www.frontendmentor.io/profile/Paul-Cavain)
- Twitter - [@CavainT](https://x.com/CavainT)
