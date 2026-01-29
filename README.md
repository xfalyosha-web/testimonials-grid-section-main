# Testimonials Grid Section – Frontend Mentor Challenge

## Overview
This project is a production-quality implementation of the "Testimonials Grid Section"
challenge from Frontend Mentor. The goal was not only to match the visual design, but
to demonstrate clean architecture, maintainable CSS, and real-world frontend practices
expected at a professional level.

The solution focuses on semantic HTML, scalable CSS, responsive layout techniques,
and accessibility-conscious styling.

---

## Key Objectives
- Build a responsive testimonials layout that adapts across desktop, tablet, and mobile
- Use modern CSS layout systems (Grid + Flexbox) appropriately
- Write maintainable, readable, and scalable styles
- Follow best practices expected in professional frontend teams

---

## Tech Stack
- HTML5 (semantic markup)
- CSS3
  - CSS Grid
  - Flexbox
  - CSS Custom Properties (Variables)
  - Responsive media queries
- No frameworks or libraries (vanilla implementation by design)

---

## Architecture & Approach

### HTML
- Semantic structure using `<main>`, `<article>`, `<header>`, and `<footer>`
- Meaningful class naming following a BEM-inspired convention
- Accessible image usage with proper `alt` attributes
- Logical content hierarchy for screen readers

### CSS
- Centralized design tokens using CSS variables (colors, typography, spacing)
- Component-based styling with clear separation between base styles and modifiers
- Layout handled with CSS Grid for macro layout and Flexbox for internal alignment
- Responsive behavior implemented with minimal, intentional breakpoints
- Avoided hard-coded values in favor of scalable units and `clamp()`

---

## Responsiveness
The layout adapts across breakpoints without layout breakage:
- Desktop: Multi-column grid layout
- Tablet: Grid reflow with stacked sections
- Mobile: Single-column layout with preserved readability

All components resize naturally without content overflow or horizontal scrolling.

---

## Accessibility Considerations
- Semantic HTML for better screen reader support
- Sufficient color contrast for text readability
- Logical tab order through document structure
- Images include descriptive alternative text

---

## Code Quality Principles
This project was built with the following professional standards in mind:
- Readability over cleverness
- Predictable class naming
- Minimal CSS specificity
- No unused styles
- Easy to extend or refactor

---

## What This Project Demonstrates
- Strong understanding of modern CSS layout systems
- Ability to translate design into clean, scalable code
- Attention to detail and UI consistency
- Frontend fundamentals suitable for production environments
- Code written with team collaboration in mind

---

## Future Improvements
- Add prefers-reduced-motion support
- Introduce CSS layering (`@layer`) for large-scale projects
- Optional dark mode using existing CSS variables
- Automated accessibility testing

---

## Author
Alin Mirea

Frontend Developer

---

## Acknowledgments
Challenge provided by Frontend Mentor.
Design by Frontend Mentor.
Implementation by me.
