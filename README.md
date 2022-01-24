# Frontend Mentor - Chat app CSS illustration solution

This is a solution to the [Chat app CSS illustration challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/chat-app-css-illustration-O5auMkFqY). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- **Bonus**: See the chat interface animate on the initial load

### Screenshot

![Screenshot](./screenshot.png)

### Links

- Solution URL: [Solution](https://github.com/jkellerman/chat-app-css-illustration-master)
- Live Site URL: [Live Site URL](https://jkellerman.github.io/chat-app-css-illustration-master/)

## My process

### Built with

- HTML5
- CSS
- Flexbox
- Mobile-first workflow

### What I learned

The main things i learned from this challenge were how to create my own arrow icons using, transform(skew) as I wasn't able to find the icon i was looking for in fontawesome or similar websites. I learned how to use border-radius to create the shape of a phone. Also, firefox was resizing a div and looked different to how it looked in chrome and safari, so I learned how to change this using @media moz-document.

To see how you can add code snippets, see below:

```html
<h1>Targeting only firefox</h1>
```

```css
@-moz-document url-prefix() {
  .iphone-container {
    height: 508px;
  }
```

### Useful resources

- [Create Chevron](https://codepen.io/stepher/pen/yLOaEOP) - This helped me for creating a chevron icon.
- [Skew](<https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/skew()>) - This helped me for changing the angle of the chevron to get it looking closer to the icon in the design.
- [Fancy border Radius Generator](https://9elements.github.io/fancy-border-radius/) - This is an amazing tool which is a life saver when you are trying to get the perfect borders. This helped me a lot when making the container for the phone.

## Author

- Frontend Mentor - [@jkellerman](https://www.frontendmentor.io/profile/yourusername)
