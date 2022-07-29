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
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Desktop Preview of Card](./images/Screenshot-Profile-Card-Preview.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I was not able to learn new things, but I was stucked in the process of positioning the patterns in the background. I set the position to absolute, but when the screen size changes, the patterns also move with it. I tried multiple methods, but nothing worked.

Here is the code which I had write to positon the patterns in the background:

```html
<div class="pattern-container">
  <div class="pattern pattern-top">
    <img src="./images/bg-pattern-top.svg" alt="" />
  </div>
  <div class="pattern pattern-bottom">
    <img src="./images/bg-pattern-bottom.svg" alt="" />
  </div>
</div>
```

```css
.container {
  font-family: var(--ff-primary);
  overflow: hidden;
  position: relative;
}

.pattern {
  position: absolute;
  z-index: -1;
}

.pattern-top img,
.pattern-bottom img {
  width: 968px;
}

.pattern-top {
  top: -42rem;
  left: -19rem;
}

.pattern-bottom {
  bottom: -39rem;
  right: -15rem;
}
```

### Continued development

I will learn how to position these patterns in a fixed place even if the screen size is changed.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
