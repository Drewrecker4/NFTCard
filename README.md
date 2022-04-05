# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](/images/Screenshot.PNG)

### Links

- [Solution URL](https://drewrecker4.github.io/NFTCard/)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Mobile-first workflow
- [Font Awesome](https://fontawesome.com/) - eye icon

### What I learned

I struggled with making the opacity 50% for the overlay while keeping the eye opacity at 100%, and this worked out pretty well.

```css
.cyan-overlay {
  background: rgb(0, 255, 247, 0);
  color: rgb(255, 255, 255, 0);
  grid-row: 1;
  grid-column: 1;
  border-radius: 5px;
  position: relative;
  margin: auto;
  width: 100%;
  height: 100%;
  bottom: 19rem;
  margin-bottom: -19rem;
  display: flex;
}

.cyan-overlay > * {
  flex: 1;
  margin: auto;
  text-align: center;
  font-size: 40px;
}

.cyan-overlay:hover {
  cursor: pointer;
  color: rgb(255, 255, 255, 1);
  background: rgb(0, 255, 247, 0.5);
}
```

### Continued development

I want to continue to practice using media queries, knowing how important they are for responsive design, and I struggled with it a bit at the start of this project.

### Useful resources

- [Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) - Anytime I get stuck on something CSS-related, the first thing I do is check if Kevin Powell made a video about it. He does a great job breaking things down, and I couldn't recommend him enough.

## Author

- Frontend Mentor - [@Drewrecker4](https://www.frontendmentor.io/profile/Drewrecker4)
- GitHub - [@Drewrecker4](https://github.com/Drewrecker4)
