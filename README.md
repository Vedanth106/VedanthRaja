# Vedanth Raja - Personal Portfolio

A premium, modern developer portfolio website designed with a dark, high-contrast cyber-neon aesthetic. Built using vanilla HTML5, custom CSS3, and JavaScript — no frameworks, no dependencies. Single-file architecture with glassmorphic cards, magnetic interactions, and smooth scroll-driven animations.

![Design Preview](https://via.placeholder.com/1200x600/07090f/5550cc?text=Vedanth+Raja+Portfolio)

## 🚀 Features

- **Dark Cyber-Neon Aesthetic**: Deep dark background (`#07090f`), violet (`#5550cc`) and cyan (`#3d8fa8`) accents, glassmorphic card surfaces with backdrop blur.
- **Interactive Particle Starfield**: Canvas-based background with drifting, pulsing stars that respond subtly to viewport size.
- **Cursor Follower**: Smooth magnetic cursor dot with interpolated movement via `requestAnimationFrame`.
- **Click Spark Effect**: On any click, 6–7 directional sparks burst from the cursor with randomized length, speed, and decay.
- **Rotating Text**: Animated skill/role rotator in the About section with slide-up/slide-down transitions between phrases.
- **Scroll-Driven Reveal Animations**: Elements fade up into view using `IntersectionObserver` with staggered delays.
- **Magnetic Interactive Elements**: Buttons, pills, and cards subtly shift toward the cursor within a defined range.
- **Skill Pills with Physics Fall**: Click any tech-stack pill to trigger a gravity-based fall with bounce and 2-second auto-return.
- **Expandable Blog Cards**: Each blog card shows a truncated summary; clicking "Read more" expands the full article inline.
- **FAQ Accordion**: Smooth expand/collapse with rotating plus icon and max-height animation.
- **Mobile-First Responsive**: Hamburger menu with full-screen overlay, safe-area insets for notched devices, 44px touch targets, and optimized star density on touch devices.
- **Accessibility**: Skip-to-content link, `prefers-reduced-motion` support (disables particles, sparks, cursor follower, and rotating text), semantic HTML.
- **Copy-to-Clipboard Networking**: One-click email copy with visual confirmation.
- **Custom SVG Favicon**: Minimal glowing mark with gold-to-violet gradient.

## 🛠️ Built With

- **HTML5**: Semantic sectioning and accessibility attributes.
- **CSS3 (Custom Styling)**: CSS Grid, Flexbox, custom properties (`:root` variables), backdrop-filter glassmorphism, keyframe animations, media queries.
- **JavaScript (ES6+)**: Canvas 2D rendering, `IntersectionObserver`, `requestAnimationFrame` loops, event delegation, clipboard API, `matchMedia` for reduced-motion and touch detection.
- **Typography & Fonts**:
  - [Sora](https://fonts.google.com/specimen/Sora): headings, labels, skill pills, buttons.
  - [Inter](https://fonts.google.com/specimen/Inter): body text, paragraphs, card descriptions.
  - [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono): nav links, labels, terminal card, monospace UI elements.

## 📂 Structure

```text
/
├── favicon.svg           # Minimal SVG favicon with gradient glow
├── index.html            # Single-file portfolio (HTML + CSS + JS)
├── index.html.backup     # Pre-redesign backup
├── demo.html             # Design preview / iteration scratch file
└── README.md             # Project documentation
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Vedanth106/VedanthRaja.git
   ```
2. Open `index.html` in any modern web browser.

## 📋 Changelog

### 2026-07-24 — Major Redesign & Feature Expansion

**Design System**
- Replaced original hacker-green theme with dark cyber-neon palette (`#07090f` base, `#5550cc` violet, `#3d8fa8` cyan).
- Introduced glassmorphic cards with `backdrop-filter: blur(16px)` and subtle violet borders.
- Added CSS custom properties for consistent theming across all components.

**New Sections**
- **Resume**: Education & experience cards with styled "View Resume" button.
- **Testimonials**: Quote cards with author attribution.
- **FAQ**: 5-item accordion with smooth expand/collapse and animated plus icon.
- **Blog / Writing**: Expandable topic cards with inline article expansion.

**Interactions & Animation**
- Particle starfield canvas with viewport-aware density.
- Magnetic hover effect on buttons, pills, and logo.
- Click spark burst effect (canvas overlay, 7 sparks per click).
- Rotating text in About section (5 phrases, 2.2s interval).
- BorderGlow edge effect on terminal card (cursor-following mesh gradient).
- Skill pill click-to-fall with physics simulation (gravity, bounce, 2s return).
- Scroll progress bar removed per feedback; replaced with staggered `IntersectionObserver` reveal animations.

**Mobile & Accessibility**
- Hamburger menu with full-screen overlay for viewports ≤768px.
- `viewport-fit=cover` and `env(safe-area-inset-*)` for iPhone notch support.
- Minimum 44px touch targets via `@media (pointer: coarse)`.
- `-webkit-overflow-scrolling: touch` and `-webkit-text-size-adjust: 100%`.
- Global `prefers-reduced-motion` support: hides particles, sparks, cursor follower, and pauses rotating text.

**Content Updates**
- Project cards restructured with colored preview tile, number pill, inline arrow button, and proportional card sizing.
- Blog summaries truncated with `...`; full text hidden until "Read more" is clicked.
- Testimonial names updated with provided real names/companies.
- Resume year corrected to `2025–Present` for BTech AIML.
- "View Resume" button centered with `font-weight: 700`.

**Technical**
- Single-file architecture maintained (no external dependencies).
- All new code added iteratively in `demo.html` before merging to `index.html`.
- Original `index.html` backed up as `index.html.backup`.

## 👤 Author

**Vedanth Raja**
- **Email**: vedanthrraja@gmail.com
- **GitHub**: [@Vedanth106](https://github.com/Vedanth106)
- **LinkedIn**: [Vedanth Raja](https://www.linkedin.com/in/vedanthraja/)

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
