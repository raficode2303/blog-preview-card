# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [github](https://github.com/raficode2303/blog-preview-card)
- Live Site URL: [Netlify](https://blog-preview-card-2024.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- responsive is by default

### What I learned

- svg tag need 'width' and 'height' and that the 'width' and 'height' of SVG count as low-level “author style sheets” like the “Presentation Attributes”.

  Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

- a tag is good for topic-tag, for example: it used by Github site.

- how to import a local font type using @font-face

- learned about the tags:
  `<blockquote>
<q>
<cite>`

```html
<img
  src="./assets/images/illustration-article.svg"
  alt="illustration article image"
  width="336"
  height="201"
  class="article-img"
/>
```

```css
body {
  font-size: clamp(14px, 4vw, 1rem);
}
```

### Continued development

how to deploy more easily

### Useful resources and Acknowledgments

- [ How to Style Block Quotes with CSS - Web Design Tutorial - by decode YouTube channel](https://www.youtube.com/watch?app=desktop&v=_R-TmN5kErE) - This helped me for styling ::before quote. I really liked this pattern and will use it going forward.
- [w3schools](https://www.w3schools.com/css/css3_fonts.asp) - This helped me to understand how to import a local font.
- [css-tricks](https://css-tricks.com/quoting-in-html-quotations-citations-and-blockquotes/) - this article is a deep dive about the semantic quotes tags: `<blockqute> <q> <cite>`

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
