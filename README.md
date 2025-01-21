# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![Desktop view](/assets/images/screenshot.jpeg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Live site URL](https://four-card-feature-section-wine-gamma.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

For this challenge, I had to learn grid which I employed in this challenge. Finally found a reason to use  **grid-template-areas**.

```css
main {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        grid-template-areas: ". team ."
        "supervisor team calculator"
        "supervisor karma calculator"
        ". karma .";
    }
```

### Continued development

I look forward to mastering CSS grid and accessibility. Solidifying my skill in CSS grid will help me in building responsive websites.

### Useful resources

- [CSS Grid Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9itC4TxYMzFCfveyutyPOCY) - This video tutorial helped me in understanding CSS grid.
- [An Interactive Guide to CSS Grid](https://www.joshwcomeau.com/css/interactive-guide-to-grid/) - It's an interactive article that helps in understanding CSS grid.

## Author

- Hashnode Blog - [Onyinyechi Viola Obika](https://obikaviola.hashnode.dev/)
- Frontend Mentor - [@Obikaviola](https://www.frontendmentor.io/profile/Obikaviola)
- LinkedIn - [Onyinyechi Obika](https://www.linkedin.com/in/onyinyechi-obika)
- X - [@obika_viola](https://x.com/obika_viola)
