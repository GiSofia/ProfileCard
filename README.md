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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

This challenge allows me to improve my html and css skills, so I thank the frontend mentor for putting real challenges, which makes us keep improving.

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./assets/images/screenshot_solution.png)


### Links

- Solution URL: [Repository GitHub](https://github.com/GiSofia/ProfileCard)
- Live Site URL: [GitHub](https://gisofia.github.io/ProfileCardt/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned

I learned how to place two images in the same container using css grid.

```css
.container-card{
    display: grid;
    place-items: center;
    width: 100%;
    height: 100vh;
    background-color: var(--Dark-cyan);
    background-image: url('./images/bg-pattern-top.svg'), url('./images/bg-pattern-bottom.svg');
    background-repeat: no-repeat;
    background-position: bottom 35.05vh right 51.85vw, top 52.1vh left 48.05vw;
    position: relative;
}
```

### Continued development

I would like to continue learning more about CSS, to know its properties very well, as well as to practice the Grid and Flexbox themes more.

### Useful resources

- [Desarrollo web](https://desarrolloweb.com/articulos/multiples-imagenes-de-fondo-con-css.html) - This website helped me to know how to place several images and give them a position.

## Author

- Website - [Giuliana Saborío](https://gisofia.github.io/portfolio/)
- Frontend Mentor - [@GiSofia](https://www.frontendmentor.io/profile/GiSofia)

## Acknowledgments

I did this challenge alone, without anyone's help, more than the resources I occupied.
