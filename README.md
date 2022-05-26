# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](\solution.JPG)

### Links

- Live Site URL: [Add live site URL here](https://shemjay.github.io/single-price-grid-component/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid

### What I learned

```html
<h1>Some HTML code I'm proud of</h1>
```

Here is some code I am proud of because I managed to stop my button from auto-stretching to fill the width of the flex container using align-self property. It was really killing me on what was wrong and it was great to see it finally work.
```css
.btn {
    align-self: center; /* Align self fixed the button from stretching within the flex container */
    padding: 0.8em 5.5em 0.8em 5.5em;
    background-color: hsl(71, 73%, 54%);
    color: hsl(0, 0%, 100%);
    outline: none;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    border: 1px solid hsl(71, 73%, 54%);
    margin-top: 1em;
}
```

Super proud of my first grid in an actual layout. This concept was kicking my butt for 5 days straight so I thouhght id return the favor lol. Seriously though, so happy this worked relatively well. I also managed to implement it with flexbox for a double win. epic.
```css
.content-wrapper {
    border-radius: 10px;
    width: 40%;
    height: 60%;
    display: grid;
    grid-template-columns: repeat(2, 2fr);
    grid-template-rows: 2fr 2fr;
    overflow: hidden;
    box-shadow: 0px 10px 15px rgb(0 0 0 / 0.2);
}
```

### Continued development

1. Work more on grid. That whole concept took me like 3 whole days just to graps the basics. Jesus. But ill make it. I will make it.

2. Responsive design with grid. I know I just started learning to use grid and I haven't learned media queries yet but I did try at the end to add some but to no avail. Apparently the best way to make a responsive grid with quesries is to use grid-template-areas. Huh. Who knew.

## Author

- Frontend Mentor - [@shemjay](https://www.frontendmentor.io/profile/shemjay)
- Twitter - [@shemstack](https://www.twitter.com/shemstack)
