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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

This goal of this project is to develop a simple site having a 'qr-code' component and styling it.


### Screenshot

[screenshot](img/screenshot.png)


### Links

- Live Site URL: [Live site URL](https://your-live-site-url.com)

## My process
1. Building the html structure for the project.
2. Adding CSS to the project.
3. Finding solution to errors on google.
4. Implementing solutions.


### Built with

- Semantic HTML5 markup
- CSS custom properties
- [Google Fonts](https://fonts.google.com/specimen/Outfit) - For fonts


### What I learned

Implementing new CSS properties:
1. position - sets the position of an element using sub-properties top, left, right & bottom.

2. transform: Applies 2D or 3D transformation to an element.

```html
<div class="container">
</div>
```

```css
.container{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```
Here, the 'position' property along with it's sub-properties 'top' & 'bottom' changes the position of <div>'container' to start from the center of window.
  Check [screenshot](img/before-transform.png)

However, 'transform: translate(-50%, -50%)' shifts center of the'container' exactly to the center of the window.
  Check [screenshot](img/after-transform.png)


### Continued development

To gain proper understanding of 'position' and 'transform' properties.


### Useful resources

- [Google fonts](https://fonts.google.com/specimen/Outfit) - This helped to use a variety of fonts to beautify a website.
- [W3 schools](https://www.w3schools.com)- This helped me find new CSS properties, how to implement them with examples. It helps you learn new properties with built-in testing feature that allows you to test any property you want to learn.


## Author

- Frontend Mentor - [@Itachidorri](https://www.frontendmentor.io/profile/Itachidorri)
- Github - [Itachidorri](https://github.com/Itachidorri)


## Acknowledgments

I am grateful to the developers of 'front-end mentor' to make projects available for a newbie learner. Also, I want to thank 'w3 schools' for providing such helpful resources to make further progress as a web developer.
