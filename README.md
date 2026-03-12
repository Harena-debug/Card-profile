# Frontend Mentor -Social Links Profile Solution

This is a solution to the [Social Links Profile Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-[Preview](#preview)
  -[The challenge](#the-challenge)
  -[Screenshot](#screenshot)
  -[Links](#links)
-[My process](#my-process)
-[Built with](#built-with)
  -[What I learned](#what-I-learned)
  -[Continuous development](#continuous-development)
  -[Useful resources](#useful-resources)
  -[AI collaboration](#collaboration-ia)
-[Author](#author)
-[Thanks](#thanks)

## Overview

Creation of an avatar profile card proposed by Frontend Mentor. This project covers the use of CSS variables, hover states, and responsiveness.

### The challenge
Create an avatar profile card with clear accessibility, a design faithful to the mockup, the use of CSS variables and good compatibility for all devices.

### Screenshot

![Profile card with good accessibility](social-links-profile-main/image.png)

### Links

-Solution URL: [GitHub Repository](https://github.com/Harena-debug/social-links-profile)
-Live site URL: [Live demo](https://harena-debug.github.io/Card-profile/)
## My process

Here is the process I implemented for this profile:

### Built with

-Semantic HTML5
-Custom CSS variables
-Flexbox for centering and layout
-Mobile-first workflow
-CSS states `:hover` and `:focus` for interactivity
-Responsive design

### What I learned

This third project allowed me to learn:

**CSS accessibility with `:focus`**

I figured out how to make links keyboard accessible with a visible focus state:
```css
a:focus {
  outline: 3px solid var(--background-hover);
  outline-offset: 2px;
}
```

**CSS variables for consistency**

Using CSS variables allowed me to maintain consistency throughout the design:
```css
:root {
  --main-color: hsl(0, 0%, 8%);
  --content-color: hsl(0, 0%, 12%);
  --color-text: hsl(0, 0%, 100%);
  --font-family: "Inter", sans-serif;
  --background-text: hsl(0, 0%, 20%);
  --radius: 15px;
  --size: 0.875rem;
  --weight: 600;
--background-hover: hsl(75, 94%, 57%);
}
```

This greatly facilitates future modifications and ensures visual harmony.

### Continuous development

This project allowed me to discover accessibility in CSS, but in future projects, I would really like to put into practice:

-**CSS Grid**for more complex layouts
-**Optimized Responsive Design**with advanced media queries
-**Advanced accessibility**with ARIA attributes
-**CSS animations**with `@keyframes`
### Useful resources

-[freeCodeCamp](https://www.freecodecamp.org/) -A new place that I discovered and which is quite effective for learning in a structured way.
-[W3Schools](https://www.w3schools.com/) -Always a perfect place to learn and test code in real time.
-[MDN Web Docs](https://developer.mozilla.org/) -Reference documentation for HTML, CSS and JavaScript.

### AI collaboration

I collaborated with AI tools in the following ways:
-**Tools used**: Claude and ChatGPT
-**Type of help**: They helped me on specific points that blocked my project (centering, CSS variables, accessibility)
-**Learning**: I took the time to understand their explanations rather than simply copying and pasting the code

## Author

-GitHub -[Harena-debug](https://github.com/Harena-debug)
-Frontend Mentor -[@Harena-debug](https://www.frontendmentor.io/profile/Harena-debug)

## Acknowledgments
Thanks to Frontend Mentor for offering me this challenge which helped me progress quite a bit. Thanks also to the AI ​​tools that accompanied me on this learning journey.