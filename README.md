# FREE WORLD: Brand Site Concept & CWU PORTFOLIO

A responsive, single-page brand website for **FREE WORLD**, a fictional discipline-focused apparel and fitness brand. Built with semantic HTML5 and custom CSS as a demonstration of production-ready layout, accessibility, and personal-brand design.

> **Concept project.** The product images are AI-generated mockups, and the Results photos are placeholder silhouettes. No real products or client results are shown.

## Live Demo

[View the live site](https://austinjones01.github.io/Portfolio/brand-mockup/)

*(Requires GitHub Pages to be enabled for this repository.)*

## Brand Concept

**Tagline:** Discipline Is Freedom
**Voice:** Silence. Repetition. Standards.
**Look:** Black-on-white minimalism, bold condensed headlines (Oswald), clean body text (Inter), and a recurring dragon motif on select pieces.

The site walks a visitor through the brand in order: a manifesto, proof of results, a four-collection merch showcase (classic and dragon lines for men and women), and an application form.

## Technical Features

* **Semantic HTML5:** Meaningful structural elements (`header`, `nav`, `main`, `section`, `article`, `figure`, `footer`) for strong SEO and accessibility baselines.
* **Responsive Layout:** Scales across desktop, tablet, and mobile using CSS Grid and Flexbox, with a mobile hamburger menu.
* **Accessible by Design:** Labeled form fields, descriptive alt text, keyboard-visible focus states, `aria-expanded` on the menu toggle, and `prefers-reduced-motion` support.
* **Separated Styles:** All styling lives in `styles.css`, built on CSS custom properties for easy theming.
* **Lightweight Stack:** No frameworks, no build step, and only a few lines of vanilla JavaScript. The only external request is Google Fonts.
* **Inline SVG Icons:** Social icons are embedded directly, so there is no icon-font dependency.

## Project Structure

```
brand-mockup/
├── index.html    # Page markup
└── styles.css    # All styling
```

## Local Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/AustinJones01/Portfolio.git
   ```
2. Open `brand-mockup/index.html` in any modern web browser. Keep `styles.css` in the same folder so the page is styled.

## Known Limitations

* The application form is front-end only and does not submit anywhere yet.
* Social links are placeholders.
* Product images are concept mockups and not final artwork.

## Author

**Austin Jones**: [GitHub](https://github.com/AustinJones01)
