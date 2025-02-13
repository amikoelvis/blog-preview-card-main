# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

The goal of this challenge was to build a blog preview card that includes:

- A category badge that users can easily identify.
- A publication date clearly visible.
- A title and description that accurately describe the content.
- An interactive hover effect for the entire card, including the title and the container.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./assets/images/screenshot.png)

### Links

- Solution URL: (https://github.com/amikoelvis/blog-preview-card-main)
- Live Site URL: (https://blog-preview-card-main-nine-ruby.vercel.app/)

### Built with

-HTML5 for the structure of the page.

- CSS3 for styling, including custom properties and Flexbox.
- Mobile-first workflow to ensure responsiveness across devices ensuring use of rem for font-size optimization of mobile devices.
- CSS Hover Effects for interactive elements.

### What I learned

In this project, I learned how to create a clean and responsive blog card layout using Flexbox. Here are some specific lessons:

Hover Effects: I applied hover effects using transform for smooth transitions, especially on the container and the title, which changes color on hover. This enhances the user experience and interactivity of the card.

Example:

```css
.container:hover {
  transform: translateY(-5px);
}
.title:hover {
  color: hsl(47, 88%, 63%);
}
```

Flexbox: I used Flexbox to align the publisher's avatar and name neatly, which helps to create a clean and well-structured layout.

Semantic HTML: I made sure to use semantic HTML5 elements like <article>, <header>, and <time> to enhance accessibility and SEO

### Continued development

For future projects, I would like to further explore:

CSS Grid for more complex layouts and fine-tuning designs.

Accessibility improvements: I plan to focus more on accessibility, particularly with semantic HTML and ARIA attributes.

JavaScript: I would love to add interactivity using JavaScript, such as expanding the description or opening the full article on click.

### Useful resources

- [Example resource 1](https://css-tricks.com/css-link-hover-effects/) - This article helped me understand how to create smooth hover transitions..
- [Example resource 2](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox) - This was a great resource for understanding and implementing Flexbox in my layout..

## Author

- Name - [Amiko Elvis]
- Twitter - [@ElvisAmiko](https://www.twitter.com/ElvisAmiko)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

Thanks to the Frontend Mentor community for providing the challenge and inspiration. Special thanks to any tutorials or resources that helped me through this process.
