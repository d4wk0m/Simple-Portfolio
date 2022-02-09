# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.png)
### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
### What I learned

I've learned how to zoom image on hover. 

```html
<div class="imgcontainer">
  <img src="./images/image-qr-code.png" alt="QR Code">
</div>
```
```css
.imgcontainer{
    overflow: hidden;
    width: 320px;
    height: 320px;
    border-radius: 10px;
    position:relative;
    z-index:1;
}

.card img{
    width: 100%;
    border-radius: 10px;
    transition: transform .5s;
    overflow: hidden;
}

.card img:hover{
    transform: scale(1.5);
}
```

### Continued development

I will be focusing on using more flexbox and building more responsive websites

## Author

- Website - [Dawid Komęza](http://dkomeza.great-site.net)
- Frontend Mentor - [@d4wk0m](https://www.frontendmentor.io/profile/d4wk0m)