# Kill Insect Game

A small browser game built with HTML, CSS and JavaScript where you try to click (catch) insects as they appear. The game was created as a lightweight, fun demo to practice DOM manipulation, timers and simple animations.

![Gameplay screenshot](./Screenshot%202024-05-09%20223505.png)

## Features

- Choose an insect (Fly, Mosquito or Bee) and start the game
- Insects spawn at random positions and rotate randomly
- Click an insect to "catch" it and increase your score
- The game becomes more hectic as new insects spawn after each catch
- Timer and score display
- Simple responsive layout that runs in any modern browser

## How to play

1. Open index.html in a browser (double-click or drag into a browser window).
2. Click "Play Game" to start.
3. Pick an insect to hunt.
4. Click insects as they appear to increase your score. The message appears when your score gets high.

## Controls

- Mouse / touch: Click or tap an insect to catch it.

## Run locally

Option A — open directly (works for most browsers):

1. Clone the repository or download the ZIP.
2. Open `index.html` in your browser.

Option B — run a simple local server (recommended if you want consistent behavior):

```bash
# Python 3
python -m http.server 8000
# Then open http://localhost:8000 in your browser
```

## Project structure

- index.html — Game HTML and UI
- style.css — Styling and layout
- script.js — Game logic (spawn, timer, scoring)
- Screenshot 2024-05-09 223424.png, Screenshot 2024-05-09 223440.png, Screenshot 2024-05-09 223505.png — example gameplay screenshots

## Notes & suggestions

- The code is intentionally simple and easy to extend. Suggested improvements:
  - Add sound effects when catching insects
  - Add levels, lives, or difficulty progression
  - Add mobile-specific touch optimizations
  - Persist high scores using localStorage

## License

MIT — feel free to reuse and modify.

---

Made with ❤️ by BinaryVortex
