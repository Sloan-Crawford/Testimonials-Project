# Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

I was challenged to to:

- Create a testimonials grid section page that matches the layout provided in images
- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Live Site URL: [https://sloan-testimonials-grid-project.netlify.app/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties and BEM Syntax
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

- Thinking about the layout and how I would use class names to organize and style each card as I went along was important to do even before beginning to write up the HTML.
- First I styled everything but the grid to get it looking nice before adding the grid properties.
- Using flexbox to align the card header items worked out well.
- Generally I think I prefer using CSS Grid for the page layout and Flexbox for alignment within elements.

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
