# NextGen Computer — Static HTML/CSS/JS

Converted from the original React + TanStack Start + Tailwind workspace into pure static files.

## Structure

```
nextgen-static/
├── index.html          # Home
├── about.html
├── services.html
├── contact.html
├── css/styles.css      # Full design system (dark cyber theme)
├── js/main.js          # Mobile menu, FAQ, scroll progress, form → WhatsApp
├── images/             # Hero, about, service photos
├── brand/              # Logo assets
└── favicon.svg
```

## How to use

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python3 -m http.server 8080
```

No build step, no dependencies.

## What was converted

- All public pages (home, about, services, contact)
- Design tokens, typography (Inter / Rajdhani / Share Tech Mono)
- Navbar (desktop + mobile), footer, WhatsApp FAB
- Hero with tilt effect, stats, services grid, process steps
- Testimonials, FAQ accordion, CTA bands
- Contact form that opens WhatsApp with pre-filled message
- Scroll progress bar + reveal-on-scroll animations

## Not included (by design)

- Auth / database / PGlite / multiplayer (server-side)
- React, Motion, Radix, TanStack Router
- Individual service detail routes (all services are on one page with anchors)

Phone/email in the original were demo placeholders (`+91 98765 43210`).
