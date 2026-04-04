# T-Minus ⏱️ — Global Countdown Events

> *Count down to every moment that matters — together with the world.*

[![Vanilla JS](https://img.shields.io/badge/Vanilla-JS-f7df1e?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Canvas API](https://img.shields.io/badge/Canvas-API-orange)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen)](.)
[![Solo Project](https://img.shields.io/badge/Solo%20Project-✓-brightgreen)](.)

**→ [Live Demo](https://roywg925.github.io/T-MINUS/)**

---

## What Is This?

T-Minus is a **zero-dependency countdown web app** with a cosmic aesthetic — real-time countdowns to global events, community voting, and a starfield background rendered via Canvas API. Fully responsive, pure frontend, no build step required.

---

## Features

- **Live Countdowns** — Precise days/hours/minutes/seconds to upcoming global events
- **Community Voting** — Users vote 🔥 on events to surface popularity
- **Category Filters** — Sports / Tech / Entertainment / Holiday
- **Create Events** — Custom countdown with emoji, date, and category
- **Glassmorphism UI** — Glass-card design with backdrop blur and subtle gradients
- **Animated Starfield** — Multi-layer procedural star particles via Canvas API
- **Orbit Ring Decoration** — CSS animated orbital ring elements
- **Mouse-Tracking Glow** — Cursor-following radial highlight effect
- **Fully Responsive** — Desktop, tablet, and mobile

---

## Tech Stack

**Zero dependencies — no npm, no build tool, no framework.**

| Technology | Usage |
|-----------|-------|
| HTML5 Semantic | Structure & accessibility |
| CSS3 (Variables + Grid + Flexbox) | Layout, glassmorphism, animations |
| Vanilla JavaScript (ES6+) | App logic, event handling, timers |
| Canvas API | Procedural animated starfield |
| LocalStorage | Event persistence across sessions |
| Google Fonts | Unbounded (headings) · Orbitron (countdown digits) · Noto Sans TC (CJK) |

---

## Design Highlights

- **Color Palette:** Deep space navy → cosmic purple gradient backgrounds
- **Glassmorphism Cards:** `backdrop-filter: blur()` with semi-transparent borders and inner glow
- **Custom Color Themes:** Each event category has a distinct accent color system via CSS variables
- **Micro-animations:** Smooth hover lifts, scale transitions, and timer digit updates
- **Orbital Rings:** Pure CSS animated ring decorations for the hero section

---

## Running Locally

No install required — just open in a browser:

```bash
# Serve locally (optional, for dev comfort)
npx serve .
# → http://localhost:3000

# Or open directly
open index.html
```

---

## Project Structure

```
.
├── index.html   ← Everything (HTML + CSS + JS, self-contained)
└── README.md
```

A deliberate single-file architecture — demonstrating that complex UI/UX (starfield, responsive layout, live timers, vote system) can be achieved without any tooling overhead.

---

*Built by Roy Wang — [Live at GitHub Pages](https://roywg925.github.io/T-MINUS/)*
