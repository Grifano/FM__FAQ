# Frontend Mentor - Stats preview card component solution

This is a solution to the [build out a FAQ accordion card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-card-XlyjD0Oam/hub/faq-accordion-card-iXayDDWmd). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
<!-- - [Acknowledgments](#acknowledgments) -->

## Overview

### The challenge

Users should be able to:

- Readings the questions
- Close/Open the next question by clicking on that

### Screenshot !

![](./images/StatsPreviewCard-min.jpg)

### Links !

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/html5andcss3-OY-0qrLfJ)
- Live Site URL: [Live](https://grifano.github.io/FrontendMentor__StatsPreviewCard/)

## My process !

### Built with !

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Responsive images
- Responsive Website

### What I learned !

Using "picture" tag, browser know what image should to load depending on viewport width 😀

```html
<picture>
	<source media="(max-width: 799px)" srcset="images/image-header-mobile.jpg">
	<source media="(min-width: 800px)" srcset="images/image-header-desktop.jpg">
	<img src="images/image-header-desktop.jpg" alt="people working in workspace">
</picture>
```
Thanks to this code, I was able to make the image responsive and look good on different screen size
```css
.card-preview__image img {
	max-width: 100%;
	min-height: 100%;
	object-fit: cover;
}
```
<!-- ```js
const proudOfThisFunc = () => {
  console.log('🎉')
}
``` -->

### Continued development

I want to continue to learn a JavaScript. Currently, I'm working on Course from Udemy. App Brewery Web Developer Bootcamp. And to do practice, practice and practice one more 😉

### Useful resources !

- [StackOverflow - Background overlap](https://stackoverflow.com/questions/24152869/make-background-color-overlap-background-image-without-extra-html) - This helped me for applying background overlap for image block.
- [StackOverflow - Responsive image resize](https://stackoverflow.com/questions/11757537/css-image-size-how-to-fill-but-not-stretch) - Here I learn how use an "object-fit" property. 

## Author

- Website - [Serhii "{Grifano}" Orlenko"](https://grifano.webflow.io/)
- Frontend Mentor - [@Grifano](https://www.frontendmentor.io/profile/Grifano)
- Twitter - [@Grifano](https://twitter.com/OrlenkoSerhii)
- LinkedIn - [@Grifano](https://www.linkedin.com/in/serhii-orlenko-44aaa4a3/)

<!-- ## Acknowledgments -->
