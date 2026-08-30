# GROW-MARK — TerraCorp HTML Template

Corporate agriculture and landscaping services website template. Clean, modern, framework-free HTML/CSS/JS with emerald green branding.

## Brand

- **Company:** TerraCorp
- **Tagline:** Growing Tomorrow's Landscape
- **Palette:** Emerald #059669 / Dark #111827 / Sage #E5E7EB / White
- **Typography:** Plus Jakarta Sans (headings) + Inter (body) via Google Fonts

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | [index.html](index.html) | Hero with carousel, stats counters, services overview, project grid, testimonials, CTA |
| About | [about.html](about.html) | Company story, timeline milestones, team grid (4 members), core values |
| Services | [services.html](services.html) | Detailed service cards, 4-step process timeline, project showcase, pricing packages |
| Contact | [contact.html](contact.html) | Contact info, form with validation, map placeholder |

## Features

- Framework-free: pure HTML, CSS, vanilla JS -- no dependencies
- Google Fonts: Plus Jakarta Sans + Inter
- CSS custom properties design system
- Scroll-triggered reveal animations (IntersectionObserver)
- Animated number counters in the stats strip
- Hero image carousel with crossfade
- Project cards with hover zoom effect
- Mobile responsive: 980px 2-column, 720px single-column + burger menu
- Fixed header with scroll-aware styling
- Contact form with client-side validation
- Newsletter subscription form
- Scroll-to-top button
- Emerald gradient accents throughout

## Structure

```
grow-mark-html-template/
  index.html
  about.html
  services.html
  contact.html
  README.md
  assets/
    css/
      style.css
    js/
      main.js
    img/
      about.jpg
      carousel-1.jpg
      carousel-2.jpg
      project-1.jpg
      project-2.jpg
      project-3.jpg
      project-4.jpg
      team-1.jpg
      team-2.jpg
      team-3.jpg
      team-4.jpg
```

## Getting Started

1. Place 11 images in `assets/img/` (see structure above)
2. Open `index.html` in a browser -- no build step required
3. Edit content directly in the HTML files
4. Customize colors by changing CSS custom properties in `:root`

## Customization

All colors, fonts, spacing, and shadows are defined as CSS custom properties in `assets/css/style.css` under `:root`. Modify the variables to rebrand the entire template in seconds.
