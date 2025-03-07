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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![desktop view](./images/Screenshot%202025-03-07%20175336.png)
![mobile view](./images/Screenshot%202025-03-07%20175413.png)

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
- CSS Animations and Transitions
  - Fade-in animations on page load
  - Side-slide animations for content
  - Smooth button hover transitions

### What I learned

One of the key things I learned was using the HTML `<picture>` element for responsive images. This allows switching images based on screen size without JavaScript:

```html
<picture>
  <source
    srcset="./images/image-product-desktop.jpg"
    media="(min-width: 600px)"
  />
  <img
    src="./images/image-product-mobile.jpg"
    alt="Gabrielle Essence perfume bottle"
  />
</picture>
```

The `<picture>` element provides:

- Automatic image switching based on media queries
- Better performance by loading only the needed image
- Graceful fallback with the `<img>` tag
- Improved accessibility with alt text

### Continued development

While working on this project, I discovered several areas I want to focus on in my future development:

- **Advanced Media Queries**: Although I implemented basic breakpoints, I want to explore more complex responsive layouts and learn how to handle multiple breakpoints efficiently.

- **Responsive Typography**: I'd like to dive deeper into fluid typography using `clamp()` and viewport units to create more dynamic text scaling.

- **Container Queries**: With the growing support for container queries, I want to learn how they differ from media queries and how they can improve component-based responsive design.

- **Advanced CSS Animations**: While I implemented basic fade animations, I want to explore more complex transitions and learn how to make them more performant and accessible.

These concepts will help me create more robust and maintainable responsive designs in future projects.

### Useful resources

- [W3Schools Picture Tag](https://www.w3schools.com/tags/tag_picture.asp) - This helped me understand how to implement responsive images using the `<picture>` element. The examples were clear and helped me grasp the concept quickly.

- [PX to REM Converter](https://nekocalc.com/px-to-rem-converter) - An excellent tool for converting pixel values to REM units. Made it much easier to maintain consistent and scalable typography throughout the project.

## Author

- Frontend Mentor - [@tasosbeast](https://www.frontendmentor.io/profile/tasosbeast)

## Acknowledgments

I'd like to give special thanks to [Kevin Powell](https://www.youtube.com/@KevinPowell) whose YouTube channel has been an incredible resource for learning modern CSS techniques. His tutorials on CSS Grid, Flexbox, and responsive design patterns have greatly influenced my approach to this project. Kevin's emphasis on writing clean, maintainable CSS and his explanations of modern CSS features have helped me improve my coding practices significantly.
