# jido6777 — NETRUNNER // NIGHT CITY

> *Personal portfolio site. Cyberpunk aesthetic. Pure HTML, CSS and vanilla JS. No frameworks, no dependencies, no trace.*

---

## // Overview

A single-file portfolio built to feel like jacking into the NET. Glitch effects, terminal animations, a Cyberpunk 2077-inspired visual system and a background music player with real-time audio visualization.

Live at → [jido6777.github.io/website](https://jido6777.github.io/website) 

---

## // Features

- **Hack intro screen** — Full-screen boot sequence with matrix rain, scan line, and a `////` slash loader that fills left to right before the site reveals itself
- **Glitch effects** — Logo, hero title, footer and interactive elements all feature multi-layer CSS glitch animations
- **Animated terminal** — The About section types out an operative profile in real time
- **Scroll progress bar** — Gradient bar fixed below the nav, with a glowing tip
- **Hack Completed overlay** — Triggers when you reach the bottom of the page
- **Contact video reveal** — A background video plays when you scroll to the contact section; links slam in one by one when it ends
- **Music player** — Background audio with Web Audio API. The bars sync to the actual frequency data of the track in real time
- **Fully responsive** — Works on mobile and desktop

---

## // Stack

```
HTML · CSS · Vanilla JavaScript · Web Audio API
```

No build step. No npm. Open `index.html` and it runs.

**Fonts** (Google Fonts)
- Orbitron — headings
- Share Tech Mono — terminal / code / UI labels
- Rajdhani — body text
- VT323 · Bebas Neue — decorative

---

## // File Structure

```
/
├── index.html          # Entire site — markup, styles and scripts
└── assets/
    ├── favicon.svg
    ├── music.mp3       # Background track
    └── video.mp4       # Contact section background video
```

---

## // Sections

| ID | Label | Description |
|---|---|---|
| `#hero` | — | Name, title, CTA |
| `#about` | 001 — Profile | Bio + animated terminal |
| `#skills` | 002 — Arsenal | Tech stack card |
| `#languages` | 003 — Communication Protocols | Language chips with proficiency dots |
| `#projects` | 004 — Active Contracts | Project cards with status indicators |
| `#contact` | 005 — Secure Channel | Links + contact video reveal |

---

## // Running Locally

No build step needed. Just clone and open:

```bash
git clone https://github.com/jido6777/website.git
cd website
# open index.html in your browser
```

> **Note:** The music player and video require a local server for some browsers due to autoplay policies. You can use the VS Code Live Server extension or run `npx serve .`

---

## // Customization

All CSS variables are defined in `:root` at the top of the `<style>` block:

```css
:root {
  --cyan:    #00eeff;
  --magenta: #ff003c;
  --yellow:  #FCE300;
  --dark:    #010204;
}
```

The terminal content, project cards, language chips and contact links are all plain HTML — easy to edit without touching any logic.

---

## // Credits

- Aesthetic inspired by **Cyberpunk 2077** (CD Projekt Red)
- Background music: *Johnny Silverhand Theme* (CP2077 OST)
- Fonts: [Google Fonts](https://fonts.google.com)

---

<p align="center">
  <code>jido6777 — built with code and Cyberpunk 2077</code>
</p>
