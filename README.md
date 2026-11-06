# Sanity Run

*Every problem is a point. Keep running. / Setiap masalah itu poin. Terus lari.*

A three-lane auto-runner for 1 to 6 players. Controls are only left, right and jump. Points come only from Issues and Good News and never go down. Kewarasan (sanity) is the health bar and the only cost.

**Play online:** https://ahadisiregar.github.io/sanity-run-webgame/

## Controls

| Player | Keys |
|---|---|
| P1 | ← → ↑ (or Space) |
| P2 | A D W |
| P3 | J L I |
| P4 | F H T |
| P5 | 7 9 8 (or numpad 4 6 8) |
| P6 | Z C S |

Gamepad *n* also drives player *n*. On phones, swipe left, right or up inside your part of the screen, or use the on-screen buttons.

## Files

- `index.html`: the whole game (no build step, no dependencies except Google Fonts).
- `docs/runner-edition1-design.md`: the design document.
- `docs/gate-cards-160.md` / `.csv`: the 160 gate cards with original and runner effects.

Tuning values are in the `CFG` object near the top of the script in `index.html`.
