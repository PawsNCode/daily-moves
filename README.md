# Daily Moves

A gentle, no-pressure exercise tracker. You define your own moves (like *deep squats · 14 kg dumbbells*), log however much you actually do each day, and watch your consistency and progress build over time. There are no strict targets — showing up is the whole point.

![Made with HTML, CSS, JavaScript](https://img.shields.io/badge/built%20with-HTML%20%C2%B7%20CSS%20%C2%B7%20JS-801d5c)

## What it does

- **Add your own moves** — name, an optional detail (equipment, notes), what it's counted in (reps, minutes, laps…), and how much each tap adds.
- **Log without targets** — tap `+`/`−` or type an exact number. Logging *any* amount counts the day.
- **Progress ring** — shows how many of your moves you've touched today.
- **Streaks** — current streak, best streak, and total days you've shown up.
- **Consistency heatmap** — an 18-week grid that brightens on the days you move.
- **Per-move progress** — a 14-day mini chart, all-time total, and best day for each move.
- **Saves automatically** — your moves, counts, and history persist between visits.

## Running it

It's a single file with no build step and no dependencies.

- **Locally:** open `index.html` in any browser.
- **GitHub Pages:** push this repo, then enable Pages (see below). Your data is stored in your browser via `localStorage`.

> Note: data is saved per browser/device. Using a different browser or clearing site data starts a fresh history.

## Deploy with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Save. Your app goes live at `https://<your-username>.github.io/<repo-name>/`.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — markup, styles, and logic. |
| `README.md` | This file. |
| `LICENSE` | MIT license. |
| `.gitignore` | Keeps OS/editor junk out of the repo. |

## Palette

| Role | Color |
|------|-------|
| Primary (active/done) | Magenta `#801d5c` |
| Accent (streak/celebration) | Fuchsia `#c02e80` |
| Background | Light pink `#fff4fb` |
| Cards | White `#ffffff` |
| Soft tints | Pink `#cd81a9` · Old rose `#ba99a2` · Brown `#af8a8f` |
| Destructive action | Sale red `#FC0000` |
| Text | Black · Dark gray `#444444` · Gray `#ababab` |

## License

MIT — see [`LICENSE`](./LICENSE).
