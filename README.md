# Random Games Kids POC

Ad-free static web app for personal use with kid profiles, local progress, math puzzle play, evaluation stats, and a drawing canvas.

## Tabs

1. **Math** - kid-friendly number crossword puzzle.
2. **Other games** - placeholder for future games.
3. **Draw** - finger drawing canvas with color selection, simple smart shape correction, fill color, saved drawings, and PNG download.

## Math progression

- Levels 1-5: addition/subtraction only, single-digit numbers
- Levels 6-10: addition/subtraction up to 20
- Levels 11-15: addition/subtraction up to 30
- Levels 16+: simple multiplication where products stay under 20

## Local privacy

- Player profiles, progress, mistakes, and drawings are stored on the device/browser using localStorage with a cookie mirror.
- No server or database is required.
- Works as a static site on GitHub Pages.

## Run locally

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## GitHub Pages

Create a public repo, upload `index.html` and `README.md`, then enable **Settings → Pages → Deploy from a branch → main → root**.


## v6 update

- Math puzzle now auto-checks about 650ms after all green boxes are filled.
- The manual button remains as **Check now**.
- Completion popup says **Congratulations <player name>!!!** with confetti.
- Rewards include bonuses for beating best time and improving mistakes.
