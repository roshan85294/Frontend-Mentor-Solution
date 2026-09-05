# Frontend Mentor - QR code component solution

This is a solution to the [QR code component on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### Screenshot

![Screenshot of the QR code component solution](./images/Capture.PNG)

### Links

- Solution URL : (https://github.com/roshan85294/Frontend-Mentor-Solution/blob/main/design/index.html)
- Live Site URL : ()

## MY process

### Built with

- Semantic HTML5 markup
- CSS with hex color codes
- Flexbox
- Mobile-first workflow
- `rem` units for accessible, scalable typography and spacing

### What I learned

In this challenge, I built a responsive card component that scales correctly on both small and large screens using a combination of `width:100%` and `max-width`:

```css
.card {
  width: 100%;
  max-width: 320px;
}
```

I centered the body using flexbox so the card stays horizontally and vertically centered on every screen size:

```css
body {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
}
```

I used `rem` instead of `px` for font-size and spacing, so that if a user increases their browser's font size, the entire layout scales proportionally without breaking.

### Continued development

Going forward, I want to work on media queries and more complex responsive layouts, such as multi-column desktop designs.

## Author

- Frontend Mentor - [@roshan85294](https://www.frontendmentor.io/profile/roshan85294)
