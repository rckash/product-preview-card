# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

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

![](./images/product-preview-card-component.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to adjust design by changing grid layouts with media query. This new knowledge has opened my mind into the possibility of creating different website designs for mobile and desktop views.

To see how you can add code snippets, see below:

```css
.product-card {
  background-color: hsl(0, 0%, 100%);
  max-width: 600px;
  border-radius: 0.4rem;
  display: grid;
  margin: 1rem;
}

@media (min-width: 600px) {
  .product-card {
    background-color: hsl(0, 0%, 100%);
    max-width: 500px;
    grid-template-columns: 1fr 1fr;
    margin: 2em;
  }
}
```

### Useful resources

- [Kevin Powell's Responsive Product Preview Card Component](https://www.youtube.com/watch?v=B2WL6KkqhLQ) - This helped me with getting the correct sizing for the card during the changes using media query. With the video's help, I have used CSS Grid instead of Flexbox as CSS Grid made it easier to change between rows and columns while maintaining the same sizing.

## Author

- Website - [Rirrucham Kashyap](https://www.github.com/rckash)
- Frontend Mentor - [@rckash](https://www.frontendmentor.io/profile/rckash)

## Acknowledgments

I would like to tip my hat to Kevin Powell for sharing his knowledge with frontend web development. I have learned a lot of things with the videos he uploads on his YouTube Channel.
