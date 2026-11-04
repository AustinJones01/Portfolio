# Austin Jones | Portfolio

This repository is a collection of projects I've created in my classes at **CWU** along with personal ones. Each project lives in its own folder, with its own details below.

## Projects

| Project | Assembly | Description |
|---|---|---|
| [FREE WORLD: Brand Site Concept](https://austinjones01.github.io/Portfolio/brand-mockup/) | Responsive personal-brand website built with semantic HTML5 and custom CSS | Personal brand mock website |
| [Austin Jones Portfolio](https://github.com/AustinJones01/Portfolio/blob/main/css/style.css) | Responsive portfolio site built with semantic HTML5 and CSS | Personal portfolio showcasing my CWU class projects |
| [Blog Mockup](https://austinjones01.github.io/Portfolio/blog) | Responsive blog layout built with semantic HTML5 and CSS | Blog mock website |

*More projects will be added as I complete them.*

---

## FREE WORLD: Brand Site Concept

A responsive, single-page brand website for **FREE WORLD**, a fictional discipline-focused apparel and fitness brand. Built with semantic HTML5 and custom CSS as a demonstration of production-ready layout, accessibility, and personal-brand design.

> **Concept project.** The product images are AI-generated mockups, and the Results photos are placeholder silhouettes. No real products or client results are shown.

### Live Demo

[View the live site](https://austinjones01.github.io/Portfolio/brand-mockup/index.html)

*(Requires GitHub Pages to be enabled for this repository.)*

### Brand Concept

**Tagline:** Discipline Is Freedom
**Voice:** Silence. Repetition. Standards.
**Look:** Black-on-white minimalism, bold condensed headlines (Oswald), clean body text (Inter), and a recurring dragon motif on select pieces.

The site walks a visitor through the brand in order: a manifesto, proof of results, a four-collection merch showcase (classic and dragon lines for men and women), and an application form.

### Technical Features

* **Semantic HTML5:** Meaningful structural elements (`header`, `nav`, `main`, `section`, `article`, `figure`, `footer`) for strong SEO and accessibility baselines.
* **Responsive Layout:** Scales across desktop, tablet, and mobile using CSS Grid and Flexbox, with a mobile hamburger menu.
* **Accessible by Design:** Labeled form fields, descriptive alt text, keyboard-visible focus states, `aria-expanded` on the menu toggle, and `prefers-reduced-motion` support.
* **Separated Styles:** All styling lives in `styles.css`, built on CSS custom properties for easy theming.
* **Lightweight Stack:** No frameworks, no build step, and only a few lines of vanilla JavaScript. The only external request is Google Fonts.
* **Inline SVG Icons:** Social icons are embedded directly, so there is no icon-font dependency.

### Project Structure

### Project Structure

```
Portfolio/
├── index.html          ← your main portfolio page (confirm name)
├── brand-mockup/
│   ├── index.html      # FREE WORLD page markup
│   └── styles.css      # FREE WORLD styling
└── ...                 ← other class projects and files
```

### Known Limitations

* The application form is front-end only and does not submit anywhere yet.
* Social links are placeholders.
* Product images are concept mockups and not final artwork.

---

## Local Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/AustinJones01/Portfolio.git
   ```
2. Open any project's `index.html` in a modern web browser. For the brand mockup, open `brand-mockup/index.html` and keep `styles.css` in the
