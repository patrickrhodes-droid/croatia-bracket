# Croatia Airbnb Championship

A single-elimination bracket for picking the best Croatia Airbnb. 28 apartments
go head-to-head — pick your favourite in each matchup until one champion remains.
Built for a group trip (4 guests, Jun 4–11, around Zadar).

**Play it live:** https://patrickrhodes-droid.github.io/croatia-bracket/

## Features

- **Single-elimination bracket** — 28 listings, auto-seeded, with byes handled.
- **Head-to-head picker** with side panels showing which listing wins on
  price, beds, distance to airport, review count and average rating.
- **Progress is saved** in your browser, so each person plays their own bracket.
  Resume and undo are supported.
- **Share my result** — the winner screen has a button that opens your phone's
  native share sheet (with clipboard / WhatsApp fallbacks) so you can fire your
  pick into a group chat.
- **Fully self-contained** — fonts are embedded, no external dependencies, works
  offline.

## Files

- `index.html` — the page served by GitHub Pages (a copy of the bracket).
- `croatiabracketexpanded.html` — the working source file (identical content).

## Run it locally

Just open `index.html` (or `croatiabracketexpanded.html`) in any browser — no
build step, no server needed. To send it to someone, attach the `.html` file or
share the live link above.

## Hosting (GitHub Pages)

This repo is set up to publish from `main` / root. To update the live site,
edit `index.html`, commit, and push — it redeploys in about a minute.
