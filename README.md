# Flappy Pixel

A retro-style Flappy Bird clone built entirely in a single HTML file using the HTML5 Canvas API — no frameworks, no dependencies.

## Play

**[Play Flappy Pixel](https://travislima.github.io/flappy-pixel/)**

Press **SPACE** or **tap the screen** to flap. Dodge the pipes, collect coins, and unlock new skins!

## Features

- **Pixel Art Graphics** — Hand-crafted sprite art rendered on canvas
- **4 Unlockable Skins** — OG Bird, Blue Jay, Vamp Bat, and Spook Ghost
- **Coin Shop** — Collect coins during gameplay and spend them in the Skin Shop
- **Dynamic Difficulty** — Pipe colors shift every 10 points; sky themes change every 20
- **Parallax Backgrounds** — Layered mountains, city skyline, and forest scroll at different speeds
- **8-Bit Sound Effects** — Procedurally generated audio using the Web Audio API
- **Score Medals** — Bronze (10+), Silver (20+), Gold (30+), and Platinum (40+)
- **Persistent Progress** — High score, coins, and unlocked skins saved to localStorage
- **Mobile Friendly** — Full touch support with responsive canvas scaling

## How to Run Locally

Just open `index.html` in any modern browser — no build step or server required.

```bash
# or use a local server
npx serve .
```

## Tech Stack

- HTML5 Canvas
- Vanilla JavaScript
- Web Audio API
- localStorage for save data
