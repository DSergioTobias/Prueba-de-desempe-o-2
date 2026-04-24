# Fusión Gourmet — Gourmet Festival Landing Page

## Description

A fully responsive, single-page landing page for **Fusión Gourmet**, a high-end gastronomic festival celebrating avant-garde cuisine, master chefs, and unique culinary experiences. The design embraces an elegant dark aesthetic with a warm copper, amber, and ivory palette, conveying sophistication and appetite appeal.

## Technologies Used

- **HTML5** — Semantic structure using `<header>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>`, `<nav>`, `<address>`, and `<table>` elements.
- **CSS3** — Advanced styling including Flexbox, CSS Grid, custom properties (variables), media queries, transitions, keyframe animations, and pseudo-elements.
- **Vanilla JavaScript** — Lightweight inline script for hamburger menu toggle, sticky header, and scroll-triggered fade-in animations via the IntersectionObserver API.
- **Google Fonts** — Cormorant Garamond (serif display) + Montserrat (sans-serif body).

## Project Structure

```
fusion-gourmet/
├── index.html       # Main HTML file — all page sections
├── styles.css       # All CSS styles, responsive rules, animations
└── README.md        # Project documentation (this file)
```

## Sections Included

| Section | Description |
|---|---|
| **Header / Nav** | Fixed navigation with logo, links, and mobile hamburger menu |
| **Hero** | Full-viewport intro with animated headline and CTA buttons |
| **Horarios** | Full schedule table + 3 featured event cards |
| **Chefs** | 4-column chef profiles with hover reveal effects |
| **Festival** | About section with values list, visual stats, and sponsors |
| **Galería** | CSS Grid photo gallery + embedded YouTube video |
| **Reservas** | Reservation form with validation-ready inputs |
| **Footer** | Contact info, navigation links, and social media list |

## Semantic HTML Features

- Proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<footer>`, `<address>`.
- Full `<table>` with `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<th scope="col">` and `<td data-label>` for accessible responsive behavior.
- Ordered and unordered lists (`<ul>`, `<li>`) for sponsors, values, navigation, social links, and footer links.

## CSS3 Highlights

- **CSS Custom Properties** — full design token system (`--col-copper`, `--ff-serif`, etc.)
- **Flexbox** — Navigation, hero actions, values list, sponsor strip, footer columns
- **CSS Grid** — Event cards, chef grid, gallery layout, footer grid, form rows
- **Keyframe Animations** — Hero entrance, scroll-line pulse, spinning logo symbol, glow pulsation
- **Scroll Animations** — IntersectionObserver-driven `.fade-in` / `.visible` class pattern
- **Responsive Table** — Collapses to card layout on mobile using `data-label` attributes and `::before` pseudo-elements

## Responsive Breakpoints

| Breakpoint | Layout Changes |
|---|---|
| `> 1024px` | Full desktop layout — 4-col chefs, 3-col events, side-by-side festival section |
| `≤ 1024px` | Tablet — hamburger menu, 2-col chefs, single-col events |
| `≤ 768px` | Mobile — single column everywhere, stacked form, card-based table |
| `≤ 480px` | Small mobile — reduced font sizes, compact visual blocks |

## How to View Locally

1. **Clone or download** this repository to your computer.
2. Open the `fusion-gourmet/` folder.
3. **Double-click `index.html`** to open it directly in any modern web browser (Chrome, Firefox, Edge, Safari).
4. No build tools, servers, or dependencies required — it runs entirely in the browser.

> **Tip:** For the best experience and to ensure Google Fonts load correctly, open the file with an internet connection, or use a local server such as VS Code's **Live Server** extension.

## Optional Extras Implemented

- ✅ Full HTML `<table>` with `<caption>`, `<thead>`, `<tfoot>` for the festival schedule
- ✅ CSS keyframe animations (hero entrance, scroll indicator, logo rotation, glow pulse)
- ✅ Additional "Nuestros Chefs" section with hover interactions
- ✅ Scroll-triggered fade-in animations using IntersectionObserver
- ✅ Responsive table that transforms into card layout on mobile

---

*Project developed for the HTML & CSS Module — Frontend Development Course.*
