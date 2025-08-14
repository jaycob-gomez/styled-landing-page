# Codecademy Full Stack Bootcamp - Styled Landing Page

A basic landing page completed as an assignment to Codecademy's Full-Stack Developer Bootcamp with HTML5 and CSS3.

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
- All required elements and selectors should be used to create a landing page that is responsive and has a pleasant UI

### Screenshot

![](./screenshot.jpeg)

### Links

- Solution URL: [GitHub](https://github.com/jaycob-gomez/styled-landing-page?tab=readme-ov-file)
- Live Site URL: [Add live site URL here]()

## My process

### Built with:

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS grid
- Responsive design
- CSS layers

### What I learned

- One of the things I was concerned about early on was that my images were not behaving how I had wanted them to. For instance, my hero image looked great on all screens, but before the tablet breakpoint was met, the image would shrink down to almost nothing before readjusting itself after hitting the breakpoint. Since I was using the flex property on my even columns and did not set a min-width on my image, I realized that as the viewport shrinked, my image became too small before the media query could work. Quick fix here: I added a min-width to my image and it worked just fine.

- I learned how to use CSS calc(), min(), and clamp() functions to allow certain aspects of the design to be responsive such as text, margins, and paddings.

- I grew more comfortable with using Grid for adjusting the layout pon different screens. The cards in the features section as well as the stats in the about section were easily implemented with Grid for an appealing layout from mobile to desktop.

## Acknowledgments

All the resources that aided in my learning and the completion of this project will be listed below, feel free to check them out and apply them to your next project!

- Kevin Powell: [min(), max(), and clamp() are CSS magic!](https://youtu.be/U9VF-4euyRo?si=mrgWNcRRSeIu3OMK)
- Coding2GO: [5 CSS Tips & Tricks for better Responsive Web Design](https://www.youtube.com/watch?v=2IV08sP9m3U&t=22s)
- Web Dev Simplified: [You Should Know These 7 CSS Responsive Sizing Features](https://youtu.be/1AyiCquK8zY?si=Ktsv0XeYPQiglofb)

All images for this project were sourced from unsplash

- Annie Spratt: https://unsplash.com/photos/group-of-people-using-laptop-computer-QckxruozjRg

- Marvin Meyer: https://unsplash.com/photos/people-sitting-down-near-table-with-assorted-laptop-computers-SYTO3xs06fU

Icons by [svgrepo.com](https://www.svgrepo.com/)

My motivation to use CSS cascade layers came from this article by CSS-Tricks: https://css-tricks.com/css-cascade-layers/ and watching this video of its implementation by Coder Coder: https://www.youtube.com/watch?v=_0noaNi051k&t=1995s
