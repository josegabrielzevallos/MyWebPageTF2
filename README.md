# Medic Family - Preventive Health Website

<!-- CRITERIA 1: Project Idea -->
## Project Overview

**Medic Family** is a modern, responsive website for a preventive healthcare clinic. The project demonstrates advanced HTML5 and CSS3 techniques including semantic markup, responsive design with mobile-first approach, CSS animations, and accessibility best practices.

### Features
- 🏥 Multi-page healthcare website
- 📱 Fully responsive design (Mobile, Tablet, Desktop)
- ♿ WCAG accessibility compliance
- 🎨 Modern CSS with custom properties
- ✨ Smooth animations and transitions

---

## Evaluation Criteria Implementation

### CSS Criteria

| # | Criteria | File | Location |
|---|----------|------|----------|
| 5 | Advanced CSS Selectors | `style.css` | `:hover`, `:focus-within`, attribute selectors |
| 6 | CSS Selector Chaining | `style.css` | `nav a.current`, `button.button-primary` |
| 7 | CSS Selector Grouping | `style.css` | `.button-primary, .button-secondary` |
| 8 | CSS Absolute Position | `style.css` | `#services-menu` dropdown |
| 9 | CSS Relative Position | `style.css` | `#services-li` parent container |
| 10 | CSS Fixed/Sticky Position | `style.css` | `header` sticky positioning |
| 11 | CSS Variables | `style.css` | `:root` custom properties |
| 12 | CSS Media Queries | `style.css` | 3 breakpoints (768px, 1024px, 1200px) |
| 13 | CSS Transitions | `style.css` | Buttons, dropdowns, gallery |
| 14 | CSS Keyframe Animations | `style.css` | `@keyframes pulse` on emergency banner |
| 15 | CSS Pseudo-elements | `style.css` | `.card::before`, `.gallery-item::after` |
| 17 | Flexible Images CSS | `style.css` | `img { max-width: 100%; height: auto; }` |
| 18 | CSS Units | `style.css` | Using `rem` throughout |
| 19 | Responsive Typography | `style.css` | `clamp()` for fluid text |
| 25 | Responsive Layouts | `style.css` | Grid and Flexbox responsive |
| 27 | Responsive Image Gallery | `style.css` | `.image-gallery` grid |
| 28 | FAQ Accordions | `style.css` | `.faq-section` styles |

### HTML Criteria

| # | Criteria | File | Location |
|---|----------|------|----------|
| 4 | HTML5 Form | `contact.html` | Contact form with inputs |
| 16 | Flexible Images HTML | `index.html` | `<figure>` elements |
| 20 | Semantic Section Markup | All HTML | `<header>`, `<main>`, `<footer>`, `<section>` |
| 21 | Semantic Content Markup | All HTML | `<article>`, `<aside>`, `<nav>` |
| 22 | Heading Structure | All HTML | h1 → h2 → h3 hierarchy |
| 26 | 404 Page | `404.html` | Custom error page |
| 28 | FAQ Accordions | `index.html` | `<details>` elements |
| 29 | CSS Library | All HTML | Google Fonts (Inter) |

---

## Project Structure

```
MyWebPageTF2/
├── index.html          # Homepage with gallery and FAQ
├── 404.html            # Custom 404 error page
├── style.css           # Main stylesheet with all criteria
├── README.md           # Project documentation
├── images/
│   ├── img-home.jpg
│   └── img-background.jpg
└── pages/
    ├── contact.html    # Contact form page
    └── services.html   # Services catalog
```

---

<!-- CRITERIA 32: Biggest Challenge -->
## Biggest Challenge

The biggest challenge was implementing a **mobile-first responsive design** while maintaining visual consistency across all breakpoints. 

### How I Overcame It:
1. Started with base mobile styles first
2. Used CSS custom properties for consistent values
3. Implemented `clamp()` for fluid typography
4. Used CSS Grid and Flexbox for flexible layouts
5. Tested at multiple viewport sizes

---

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, Animations
- **Google Fonts** - Inter font family

---

## Validation

- ✅ W3C HTML Validation: https://validator.w3.org/
- ✅ W3C CSS Validation: https://jigsaw.w3.org/css-validator/
- ✅ WCAG Color Contrast: Use https://webaim.org/resources/contrastchecker/

---

© 2025 Medic Family. All rights reserved.
