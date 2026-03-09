# Helen's Clucky Match!

A cute chicken-themed memory matching game, built as a Mother's Day gift.

## How to Play

Flip cards to reveal chickens and find matching pairs. The fewer moves you take, the more stars you earn! Complete puzzles to collect decorative eggs for your nest.

**Difficulty levels:** Easy (4 pairs) through Extreme (16 pairs), featuring 16 unique chicken breeds including Silkies, Polish, Frizzles, Bantams, and more — all hand-drawn in SVG.

## Features

- 16 unique SVG chicken characters, each with a name and breed
- 5 difficulty levels
- Star rating based on performance
- Collectible egg system with unique patterns per difficulty
- Sound effects via Web Audio API
- Animated clouds, feathers, and card flips
- Mobile-friendly — optimised for iPhone and touch devices

## Running

Open `index.html` in a browser. No build step or dependencies required — it's a single self-contained HTML file.

To serve locally:

```bash
npx serve .
# or
python3 -m http.server
```

## Hosting on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings > Pages**
3. Set source to the `main` branch and root (`/`)
4. The game will be available at `https://<username>.github.io/<repo-name>/`

## License

MIT
