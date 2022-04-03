# Testimonials grid section solution

This is my solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

I was challenged to to:

- Create a testimonials grid section page that matches the layout provided in images
- Make it responsive to both desktop and mobile screens

### Screenshots

![Desktop](./images/Desktop-screenshot.png)
![Mobile](./images/Mobile-screenshot.jpeg)

### Links

- Live Site URL: [https://sloan-testimonials-grid-project.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties and BEM Syntax
- Flexbox
- CSS Grid

### What I learned

- Thinking about the layout and how I would use class names to organize and style each card as I went along was important to do even before beginning to write up the HTML.
- First I styled everything but the grid to get it looking nice before adding the grid properties.
- Using flexbox to align the card header items worked out well.
- Generally I think I prefer using CSS Grid for the page layout and Flexbox for alignment within elements.
- Setting the grid columns and rows for each card was easy using the span technique.
- I found that for mobile setting, to get the cards to stack, setting the container to display: block did it in one step as opposed to resetting the span of each card.

- Styling notes:
- layering the box shadow was fun but in the end I kept it simple for this page
- setting border radius to 50% is a great way to make a circular border
- setting opacity to a certain percent is an effective way to lighten text
- Getting the background image correct took me some time but in the end it worked with this:

```css
.card--bg-purple {
  background: hsl(263, 55%, 52%);
  color: #fff;
  background-image: url(./images/bg-pattern-quotation.svg);
  background-repeat: no-repeat;
  background-position: top 10px right 100px;
}
```

## Author

- GitHub - [Sloan-Crawford](https://github.com/Sloan-Crawford)
- YouTube Playlist - [Sloan's-Web-Dev-Journey] (https://www.youtube.com/playlist?list=PLzZ37-9URvZAHQKn8ukTB2YarkAvGUR3I)
