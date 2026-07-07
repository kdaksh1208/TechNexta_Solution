# TechNexta Solutions — Website

A modern, premium, dark-themed, fully responsive static website built with plain HTML, CSS, and JavaScript.

## Structure
```
├── index.html          Home page
├── about.html           About Us page
├── services.html         Services (18 service cards)
├── portfolio.html        Portfolio with category filters
├── pricing.html          Pricing (Starter / Professional / Enterprise)
├── contact.html          Contact form, info, map placeholder, WhatsApp
├── css/
│   └── style.css        All styles (design tokens, components, responsive)
├── js/
│   └── script.js         All interactivity (nav, reveal animations, FAQ, carousel, filters, canvas background, form)
└── images/               Empty — add your own logo/photos here if desired
```

## How to use
1. Open `index.html` in any browser — no build step or server required.
2. To host it, upload the whole folder to any static host (Netlify, Vercel, GitHub Pages, cPanel, etc.).
3. Update the phone number, email, and WhatsApp link (`https://wa.me/919876543210`) in every page's footer and contact section to your real details.
4. Replace the Google Map placeholder in `contact.html` with a real embedded `<iframe>` map when ready.
5. The contact form is front-end only (no backend). To actually receive submissions, connect it to a form service (e.g. Formspree, EmailJS) or your own backend endpoint by updating `js/script.js`.

## Features
- Sticky, transparent-to-solid navbar with mobile hamburger menu
- Animated particle network background in the hero (canvas, respects reduced-motion)
- Glassmorphism cards throughout
- Scroll-triggered reveal animations
- Animated stat counters
- Accordion FAQ
- Auto-playing testimonial carousel
- Filterable portfolio grid
- Back-to-top button and floating WhatsApp button
- Preloader on page load
- Semantic, SEO-friendly HTML with meta descriptions on every page

## Color Palette
| Token | Value |
|---|---|
| Primary | `#2563EB` |
| Secondary | `#1E293B` |
| Accent | `#38BDF8` |
| Background | `#0F172A` |
| Text | White |
| Card | `rgba(255,255,255,0.08)` |

Font: **Poppins** (Google Fonts) · Icons: **Font Awesome 6**
