# Semantic Bridge

A daily word-association puzzle. Connect a start word to an end word through three hidden bridge words — each adjacent pair forms a compound word or strong association (e.g. `dog → bone → break → dance → party`).

## How it works
- Self-contained `index.html`. No build, no server, no dependencies.
- `CLEAN_PUZZLES` (around line 444) holds the 35-puzzle pool, each a fixed 5-word path: `[start, b1, b2, b3, end]`. v1.01 redesign locked these to single canonical solutions — no branching, no alternate paths.
- Day 1 = Monday, May 25, 2026 (UTC). The puzzle advances at UTC midnight and is the same worldwide. Pool repeats after day 35.
- Stats (streak, win history, hints used, wrong guesses) persist in `localStorage`. No accounts, no analytics.

## Hosting
GitHub Pages. Whole game ships as one HTML file.

## License
Code is MIT-licensed — reuse freely with attribution.
