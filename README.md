# Card School

Learn to play cards from zero — a browser game that teaches step by step, then lets you play **Call Bridge** and **29** against computer players.

**Play:** https://sristy0807.github.io/games/card-school/

## Levels

| # | Level | Teaches |
|---|---|---|
| 1 | Meet the deck | Suits and card names (with Bangla names) |
| 2 | Who is bigger? | Rank order, 2 → A |
| 3 | Follow the suit | Lead card, must-follow rule |
| 4 | Win the trick | Highest card of the led suit wins |
| 5 | The power of trump | Trump beats other suits |
| 6 | Your first full hand | 13-trick hand with legal-card hints |
| 7 | Call Bridge: calls & scores | Calling and scoring quiz |
| 8 | Play Call Bridge | 3 rounds vs bots, suggested call |
| 9 | 29: new order, points | J-9-A-10 order, card points, bidding, hidden trump |
| 10 | Play 29 | 3 deals with North as partner |

## Tech

One self-contained `index.html` (HTML, CSS, vanilla JS). No build step, no assets:
music and sound effects are synthesized with the Web Audio API; progress and audio settings are kept in `localStorage`.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Host on GitHub Pages

Settings → Pages → Deploy from branch → `main` / root. The game will be at `https://sristy0807.github.io/cardSchool/`.
