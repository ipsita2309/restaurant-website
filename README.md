# 🍽️ C2 Restaurant Website – Responsive & Accessible Redesign

This project is a redesigned version of the **Delicious Eats Restaurant Website** for the UW Front-End course assignment.  
The goal was to make the site **responsive, semantic, and accessible** while following best practices.

---

## 📂 Pages
- **Home (index.html)** – About Us, Our Hours, welcoming images.
- **Menu (menu.html)** – Menu categories with responsive images.
- **Contact (contact.html)** – Accessible contact form and location map.
- **Thank You (thankyou.html)** – Confirmation page after form submission, with navigation buttons.

---

## ✅ Enhancements Implemented

### Accessibility (WCAG 2.1 AA)
- Added **skip to content** link for keyboard users.
- Ensured **color contrast ≥ 4.5:1**.
- Semantic HTML5 structure (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`).
- Logical heading order (`h1` → `h2`).
- Added **focus indicators** (`:focus-visible`) for all links, buttons, and form fields.
- ARIA attributes:
  - `role="navigation"`, `aria-label` on navs.
  - `aria-current="page"` for active link.
  - Labels and `aria-required` on form fields.
- Fully keyboard navigable.

### Responsiveness
- Used **flexbox** and **CSS grid** layouts.
- Mobile-first design with breakpoints for tablet & desktop.
- Pure CSS **hamburger menu** (no JS).
- Responsive images with `srcset` + `sizes`.
- Lazy loading (`loading="lazy"`) for performance.

### Forms
- Accessible labels, required indicators, and focus styles.
- Form redirects to **thankyou.html** (placeholder confirmation).

### Print-Friendly
- Added `@media print` rules:
  - Hides nav, header, footer, skip link, and buttons.
  - Keeps main content clean for printing.
  - Links display their URLs.

### Visual Enhancements
- **CSS-driven icons** for nav links, section headings, and buttons.
- Subtle **icon animations** on hover/focus (scale + color change).
- **Fade-in animation** for page content on load.
- Added `prefers-reduced-motion` support to disable animations for sensitive users.

---

## 📂 Project Structure
