# מלכת הסקוויישים 👑

A 2-player web game with a galaxy theme. Each player has three buttons (✓ + ✗) that show a friendly response, plus a personal squishies collection.

## Pages
- **index.html** — the main game (2-player, split screen)
- **squishies.html** — each player's squishies collection (add / edit / delete, saved in the browser)

## Features
- Two players facing each other (top half rotated 180°)
- Editable player names, saved in `localStorage`
- Per-player squishies list with full CRUD, saved in `localStorage`
- Reset button to clear all data and start fresh
- Pure HTML/CSS/JS — no build step, no dependencies

## Run locally
Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```
