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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

### Links

- Solution URL: [https://github.com/takahashiyb/product-preview-card-component-main]
- Live Site URL: [https://takahashiyb.github.io/product-preview-card-component-main]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

There were a lot of @media learnings to be had here. I realized that you can use the picture tag:

```html
<picture>
  <source srcset="./images/large.jpg" media="(min-width: 600px)" />
  <img src="./images/small.jpg" alt="cover image" class="cover-image" />
</picture>
```

To edit the image, you can style the img tag, and if you want to change the styling of the one in the source element, you can then style it as @media (min-width: 600px) {}.

### Continued development

Despit knowing some parts of the @media and interactivity of websites, the challenge has made it clear to me that there are more that needs to be learned. not just with the learnings undiscovered, but solidifying strategies that already was.

Still need to learn about fonts and more HTML tags

### Useful resources

## Author

- Frontend Mentor - [@takahashiyb]

## Acknowledgments
