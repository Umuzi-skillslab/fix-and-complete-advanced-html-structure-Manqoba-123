# Media Production Website

## Overview
This is a modern, responsive multi-page website for a **Media Production Company** specializing in video production, audio recording, and multimedia solutions. The site features a sleek dark theme with neon green accents(Spotify styling), designed to showcase professional services, portfolio work, media samples, and easy client contact.

The website consists of four pages:
- **Home** (Landing Page with hero background)
- **About** (Team, Services & Portfolio)
- **Media** (Video showcase, audio player & testimonials)
- **Contact** (Advanced interactive form)

**Live Demo:** Open `index.html` in any modern browser.

## Issues Found in Starter Code
- Heavy use of generic `<div>` instead of semantic HTML5 elements
- Missing meta tags (charset, viewport, description)
- No responsive design or mobile support
- Repeated navigation code across pages
- Basic styling only — no Flexbox, Grid, animations, or hover effects
- No real media elements (`<video>`, `<audio>`, `<iframe>`)
- Poor form accessibility (missing labels, fieldsets, proper input types)
- Low contrast and inconsistent layout

## Fixes and Implementations
I converted the entire project to **semantic HTML5** (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<figure>`, `<fieldset>`, etc.).  
I created a single shared `styles.css` file for consistency and maintainability.  
Added real media elements, advanced form with HTML5 validation, and a modern dark UI.

## Flexbox Layouts Implemented
- **Header**: Flexbox for logo + navigation (responsive stacking on mobile)
- **Hero Section**: Flexbox for perfect vertical & horizontal text centering
- **Radio & Checkbox groups**: Flexbox for clean alignment

## CSS Grid Layouts Implemented
- **Features / Services cards**: `repeat(auto-fit, minmax(300px, 1fr))`
- **Portfolio gallery**: Responsive image grid with hover effects
- **Testimonials**: Auto-fit card grid

## Selectors and Pseudo-classes Added
Used over 10 advanced selectors including:
- `:hover`, `::after`, `:focus`, `:required`
- `.active` class for navigation highlighting

## Animations, Effects, Transforms & Transitions
- Fade-in animations (`fadeInDown`, `fadeInUp`) on hero text
- Smooth hover lifts (`transform: translateY()` and `scale()`)
- Underline animation on nav links using `::after`
- Image zoom effect on portfolio hover
- Button scale and shadow transitions
- Backdrop blur and overlay effects

## Accessibility Improvements
- Proper semantic structure and heading hierarchy
- `<label>` for every form input
- `<fieldset>` + `<legend>` for form grouping
- Descriptive `alt` texts and `figcaption`

## Cross-Browser Compatibility
Tested on Chrome, Edge.  
Uses standard CSS with fallback-friendly properties. No major browser-specific hacks needed.

## How to View Locally
1. Download or clone the project folder
2. Ensure folder structure includes:
   - `index.html`, `about.html`, `media.html`, `contact.html`
   - `css/styles.css`
   - `images/` folder (for background and portfolio images)
3. Open `index.html` in your browser

## Known Limitations
- Media files (`video`, `audio`) are placeholders — replace with real assets