# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

![alt text](assets/Capturar.PNG)


### Links

- Live Site URL: [Add live site URL here](https://social-links-project-main.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned
Semantic HTML Structure

I learned how to properly use semantic tags like <main>, <footer>, <ul>, and <h1> to make my HTML more meaningful and accessible.
This improves SEO and ensures that screen readers can interpret my content correctly.

CSS Variables and Design System

I learned how to use :root to store CSS custom properties (variables) for colors, font sizes, and weights.
This makes the design consistent and easy to maintain.

:root {
  --clr-primary-Green: hsl(75, 94%, 57%);
  --clr-neutral-Off-Black: hsl(0, 0%, 8%);
  --ff: 'Inter', sans-serif;
  --fw-700: 700;
}

CSS Reset and Base Styling

I practiced resetting default browser styles using the universal selector * and improved typography and spacing consistency.

*,
*::before,
*::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

Responsive and Centered Layout

I used CSS Grid and the place-items: center; property to center my profile card both vertically and horizontally on the screen.

.wrapper {
  display: grid;
  place-items: center;
  min-height: 100dvh;
}

Hover States and Smooth Transitions

I learned how to style link hover states and use transitions to make interactions feel smoother.

.list-item:hover {
  background: var(--clr-primary-Green);
  color: var(--clr-neutral-Off-Black);
  transition: background .3s ease, color .3s ease;
}


### Continued development

Responsive Design

I want to become more confident in creating layouts that adapt perfectly to different screen sizes.
I plan to practice more with media queries, Flexbox, and Grid combinations, as well as explore responsive units like em, rem, and clamp().

Accessibility and SEO Best Practices

I’ve learned the importance of writing semantic HTML, but I want to go deeper into accessibility features such as aria-labels, better heading hierarchy, and meaningful alt descriptions to make my pages more inclusive and SEO-friendly.

Scalable CSS and Code Organization

I want to improve how I organize my CSS by learning BEM naming conventions, using SASS/SCSS, and understanding better project architecture so my styles remain clean and easy to maintain as projects grow.

## Author

- Frontend Mentor - [@LadyManu](https://www.frontendmentor.io/profile/LadyManu)

