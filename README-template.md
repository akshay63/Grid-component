# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

## Overview

### The challenge

For this challenge I've used:

- HTML & CSS grid

### Screenshot

Here's the screenshot of the testomonial section.
(images/screenshot.png)

### Links

- Solution URL: (https://github.com/akshay63/Grid-component)
- Live Site URL:(https://grid-component-alpha.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Grid
- Desktop-first workflow

### What I learned

Well this is the first time I've used CSS grid this much. I learned more about CSS grid like positioing grid items and how can be they placed so easily. Though I have not explored more complex concepts in grid like minmax function or auto-fit value in responsive layout using CSS grid, which is difficult to grasp so I used simple way to place items.

Below is a code snippet of CSS grid:

```css
@media only screen and (max-width: 768px) {
  .testomonials {
    max-width: 35rem;
    grid-template-columns: repeat(1, 35rem);
    grid-template-rows: repeat(5, min-content);
    margin: 5rem auto;
  }
}
```

### Continued development

I want to explore more about CSS grid because it has lot to offer than any method out there thats why its so useful and easy to work with if we apply learned concepts well.

### Useful resources

- (https://www.mdn.com) - I used MDN for CSS grid properties.

## Author

- Frontend Mentor - (https://www.frontendmentor.io/profile/akshay63)
