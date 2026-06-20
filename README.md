# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](.\assets\images\image.png)

### Links

- Solution URL: [solution URL](https://your-solution-url.com)
- Live Site URL: [Live site URL](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Learned how to properly use CSS custom properties to avoid repeating values across the stylesheet. Also got more comfortable with CSS Grid for centering layouts.

```css
:root {
    --color-yellow: #F4D04E;
    --color-black: #111;
    --spacing-md: 24px;
    --border-radius-card: 20px;
}
```

Learned that `type` attribute is invalid on `<img>` tags, and that heading tags should reflect document hierarchy — not be used just for sizing.

### Continued development

- Accessibility: proper focus states and ARIA labels
- CSS architecture: BEM naming conventions
- Responsive design beyond basic mobile-first

### AI Collaboration

- Tool used: Claude (Anthropic)
- Used for: code review, catching semantic HTML issues.
- What worked well: quickly identified the invalid `type` attribute on `<img>`, misused heading hierarchy, and missing `overflow: hidden` on the card container
- What didn't: still need to manually write the README and fill in project-specific details

## Author

- Frontend Mentor - [@Death8959](https://www.frontendmentor.io/profile/Death8959)
