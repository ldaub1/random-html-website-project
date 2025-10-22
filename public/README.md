# Snake Game + Spinning Cube

A zero‑dependency single‑file web app featuring a modernized Snake game rendered on a 600×600 canvas and a 3D glass‑morphism spinning cube in the top‑right corner. The cube spins faster as your score increases.

## Quick start

- Double‑click `spinning-cube.html` to open it in your browser, or
- Serve locally for best results:
  - VS Code Live Server (recommended), or
  - Python: `python3 -m http.server` then open `http://localhost:8000/spinning-cube.html`.

## How to play

- Use Arrow keys to move. The game starts on your first arrow press.
- Collect food to grow and earn points.
- Avoid walls and your own body.
- On mobile, swipe on the canvas to change direction.
- Click "Play Again" when you lose.

## Features

- 3D CSS cube with glassy styling; speed syncs with score (Normal → INSANE).
- Clean gradient background and polished UI.
- Dynamic difficulty: game loop speeds up every 5 points.
- Score and cube speed indicators; animated game‑over modal with restart.
- Touch (swipe) and keyboard controls.
- Single HTML file; no frameworks or build steps.

## Customize

Tweak directly in `spinning-cube.html`:

- Grid and speed: `gridSize`, starting `gameSpeed`, and thresholds in `updateCubeSpeed()`.
- Cube: `.cube-container` size and animation duration; replace the face content (🎮).
- Colors: page gradient and cube face backgrounds in the CSS.
- Canvas: change `width`/`height` on `#gameCanvas`.

## Files

- `spinning-cube.html` — All HTML, CSS, and JS in one file.
- `README.md` — This file.

## Browser support

Works in modern evergreen browsers (Chrome, Edge, Firefox, Safari). Mobile supported via touch controls.
