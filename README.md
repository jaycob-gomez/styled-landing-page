# Codecademy Full Stack Bootcamp - Styled Landing Page

A basic landing page completed as an assignment to Codecademy's Full-Stack Developer Bootcamp.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

- Users should be able to view the optimal layout for the interface depending on their device's screen size
- All required elements and selectors should be used to create a landing page that is responsive, uses semantics, and is accessible for all users

### Screenshot

![](./screenshot.jpeg)

### Links

- Solution URL: [Add solution URL here]()
- Live Site URL: [Add live site URL here]()

### My process

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS grid
- Responsive design
- Hover states
- CSS layers

### What I learned

- One of the things I was concerned about early on was that my images were not behaving how I had wanted them to. For instance, my hero image looked great on all screens, but before the tablet breakpoint was met, the image would shrink down to almost nothing before readjusting itself after hitting the breakpoint. Since I was using the flex property on my even columns and did not set a min-width on my image, I realized that as the viewport shrinked, my image became too small before the media query could work. Quick fix here: I added a min-width to my image and it worked just fine.

- I learned to use CSS calc() and clamp() functions

  - calc()

  - clamp() allowed me to set a responsive padding with a minimum, preferred, and maximum value

## Acknowledgments

All images for this project were sourced from unsplash

- Annie Spratt: https://unsplash.com/photos/group-of-people-using-laptop-computer-QckxruozjRg

- Marvin Meyer: https://unsplash.com/photos/people-sitting-down-near-table-with-assorted-laptop-computers-SYTO3xs06fU

Icons by svgrepo.com

My motivation to use CSS cascade layers came from this article by CSS-Tricks: https://css-tricks.com/css-cascade-layers/ and watching this video of its implementation by Coder Coder: https://www.youtube.com/watch?v=_0noaNi051k&t=1995s
