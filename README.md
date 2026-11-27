# Lab 3: Responsive One-Page Portfolio

A mobile-first, one-page portfolio built with HTML and CSS. It uses Flexbox, CSS Grid, media queries, relative units, transitions and keyframe animations. It builds on my Lab 2 project.

## Sections
Header, Hero, About, Skills, Projects, Contact, Footer.

## Techniques used
- **Flexbox:** header (logo + nav), hero (text left, image right), buttons, form, footer
- **CSS Grid:** Skills and Projects cards (1 column, then 2, then 3)
- **Media queries (mobile-first):** `min-width` breakpoints
- **Relative units:** rem, em, %, vh
- **Hover and transitions:** nav underline, buttons, cards, links, form focus
- **Keyframes:** hero fade-in and colour-changing role text
- **Transforms:** `translateY`, `scale`, `rotate` on cards, buttons, avatar

## How to view responsive behaviour
1. Open `index.html` in Chrome or Edge.
2. Press `F12`, then the device toolbar icon (`Ctrl+Shift+M`).
3. Resize and check these breakpoints:

| Screen | Width | Layout |
|---|---|---|
| Mobile | below 768px | Hero image above text, 1-column grid, stacked header |
| Tablet | 768px to 1023px | Header in one row, 2-column grid |
| Desktop | 1024px and above | Hero side by side, 3-column grid |

## Files
`index.html`, `style.css`, `README.md`
