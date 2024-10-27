# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
  - [Author](#author)

## Overview

### Screenshot

![](/assets/images/Captura%20de%20tela%202024-10-26%20210853.png)

### Links

- Live Site URL: [Site](https://your-live-site-url.com)
- [Challenge URL](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm/hub)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I learned

I've learned more about specific styles in css such as pseudo-classes and lists styles in this challenge, plus I've trained my knowledge of what I have already learned (or at least what I thought I've learned).

Some code blocks:

- pseudo-class -> ``` :last-child ``` and ``` :not() ```
```css
.row:not(:last-child) td {
    border-bottom: 3px solid rgba(0, 0, 0, .1);
}
```
- css property -> ``` clamp() ```
```css
.card {
    width: clamp(40%, 576px, 100%);
    background-color: var(--white-100);
    padding: 2.25rem;
    border-radius: 20px;
    margin: auto;
}
```

### Useful resources

- [Slaying The Dragon - Learn CSS Grid](https://www.youtube.com/watch?v=EiNiSFIPIQE) - This helped me in organizind the table spacing using grid.

## Author

- Frontend Mentor - [@LeonardoLopesHonda](https://www.frontendmentor.io/profile/LeonardoLopesHonda)
- Github - [Leonardo Honda](https://www.twitter.com/yourusername)
- Linkedin - [Leonardo Honda](https://www.linkedin.com/in/leonardo-honda-9a3383248/)