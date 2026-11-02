# Word Guess — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Guess the hidden five-letter word in six tries. Green = right spot, yellow =
in the word but elsewhere, gray = not in it. Daily and endless modes, hard
mode, streaks and stats.

## Details

- Genre: Word / Puzzle / Casual
- Controls: Type with your physical keyboard or tap the on-screen QWERTY
  keys. Enter submits a guess, Backspace deletes.
- Features: 6 guesses per word, color-coded flip-tile reveals, daily puzzle
  (same word for everyone each day, seeded locally), endless random mode,
  hard mode (revealed hints must be reused), on-screen keyboard with letter
  feedback, stats with win rate, current/max streak and guess-distribution
  chart, all saved locally. Not-in-word-list validation for every guess.
- Word bank: 659 common answer words plus 1254 extra valid guesses
  (1913 words total), embedded in the file.
- Tech: Vanilla JavaScript, DOM rendering, WebAudio-synthesized sounds.
  Single-file HTML5, no frameworks, no CDN, no tracking, no external links.
  Works offline once loaded.

## Tags

word, wordle-like, puzzle, daily, letters, brain, casual, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop events wired
- [x] Responsive (layout scales from 360px phones to desktop, portrait-friendly)
- [x] No external links inside gameplay, no analytics
- [ ] Cover image (to be added at submission time)

## itch.io
- Upload word-guess-itch.zip, mark "This file is playable in browser",
  entry file: index.html, kind: html, viewport: fits screen (mobile friendly)
- Pricing: $0 (donations optional)

## GameDistribution
- Upload word-guess-gd.zip (contains only index.html); the GD SDK loader
  activates automatically on gamedistribution / gd.games domains.
