# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

This is a practice project demonstrating the use of CSS Grid and Flexbox.

### The challenge

To create a complex css grid

### Screenshot

![webpage screenshot](webpage-screenshot.jpg)


### Links

- Live Site URL: [The webpage](https://omarhazem02.github.io/bento-grid/)

## My process

Analyzed the challenge’s design.

Structured the HTML layout.

Applied styling using CSS.

Rebuilt the layout using CSS Grid for better control and organization.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid


### What I learned


I gained more experience with CSS Grid, especially in creating layouts using the grid-template-areas property.

```html
<article class="container">
  <div class="creat-post-box">...</div>
  <div class="social-media-box">...</div>
  <div class="timings-box">...</div>
  <div class="using-ai-box">...</div>
  <div class="accounts-box">...</div>
  <div class="schedule-box">...</div>
  <div class="growth-box">...</div>
  <div class="followers-box">...</div>
</article>

```
```css
.container {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(4, 20%);
  grid-template-areas:
    "creat media media timings"
    "creat accounts schedule timings"
    "ai accounts schedule timings"
    "ai growth followers followers";
  gap: 20px;
  margin: 0 auto;
  margin-top: 20px;
  margin-bottom: 20px;
  width: 80%;
}

.creat-post-box { grid-area: creat; }
.social-media-box { grid-area: media; }
.timings-box { grid-area: timings; }
.using-ai-box { grid-area: ai; }
.accounts-box { grid-area: accounts; }
.schedule-box { grid-area: schedule; }
.growth-box { grid-area: growth; }
.followers-box { grid-area: followers; }

```



### Continued development

This project took longer to complete because I’m not yet fully confident with CSS Grid. I plan to keep practicing and work on gaining a deeper understanding of how to structure and optimize layouts with it.

### Useful resources

- MDN Web Docs helped me expand my knowledge on certain topics while creating this page..
- Chat gpt Claude supported me as  mentors by helping evaluate and review my code throughout the project.


## Author

- Website - [Omar Hazem](https://www.linkedin.com/in/omar-hazem-aa287a273/)
- Twitter - [@Omarhaz67778375](https://x.com/OmarHaz67778375)


## Acknowledgments

I would like to acknowledge AlMadersa, where I am currently studying in the Front-End Development Diploma program.
Special thanks to my course tutor, Mohamed Abu Sarea (محمد أبو سريع), for his valuable guidance and support.
