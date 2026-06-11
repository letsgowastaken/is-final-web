# IS Final Web Project — Jake Stevens

## What's in here
| File | Purpose |
|---|---|
| `index.html` | Professional home page (Bootstrap 5) |
| `resume.html` | HTML résumé (education, experience, skills, honors) |
| `scratch.html` + `scratch.css` | From-scratch page (no Bootstrap) — Spikeball |
| `game.html` | AI-collab web app: single-file battle royale game |
| `images/` | headshot, Luma job + handshake photos, YouTube channel, Spikeball tournament |
| `images/spikeball.svg` | Original illustration (non-Bootstrap image requirement) |

## ⚠️ Before submitting
1. **Verify on the live site** (not just locally): YouTube embed and Tableau embed only render once hosted.
2. Optionally link `game.html` from `index.html` if the rubric wants the web app reachable from the pro site (currently it's a standalone URL you submit).

## Deploy to GitHub Pages
1. Create a public repo (e.g., `is-final-web`).
2. Upload all files/folders in this directory to the repo root.
3. Repo → Settings → Pages → Source: `main` branch, `/ (root)` → Save.
4. URLs to submit:
   - Professional: `https://<username>.github.io/is-final-web/`
   - Scratch: `https://<username>.github.io/is-final-web/scratch.html`
   - Web app: `https://<username>.github.io/is-final-web/game.html`

## Rubric coverage (scratch page)
- UL nested in OL ✔ (rally steps → three-touch list)
- Non-Bootstrap image ✔ (`images/spikeball.svg`)
- YouTube embed ✔ (Spikeball Top 10 Plays of 2019)
- On-page anchor ✔ (`#top` + "Back to top" button; nav anchors to #gear/#video/#data)
- Custom background color ✔ (`body{background-color:#181818}`)
- Stylesheet from scratch ✔ (9 style definitions; font color + font family; 4 styled divs)
- Live interactive Tableau embed ✔ (Tableau Public sample via Embedding API v3)
- Nav back to professional pages ✔ (top nav + footer)

## Game controls
Third-person. WASD move · mouse look (click once to capture the mouse; Esc releases it; drag-look works as a fallback) · click attack/use · Space jump · Shift sprint · E open chest · 1–5 slots · R reload. You vs 7 bots that hunt you down — last alive wins. Loot: pistol, SMG, AR, shotgun, sniper, shield potion, medkit across 4 rarities. Chests have gold light beacons.
WASD move · mouse look · click attack · Space jump · Shift sprint · E open chest · 1–5 slots · R reload. You vs 2 bots, last alive wins.
