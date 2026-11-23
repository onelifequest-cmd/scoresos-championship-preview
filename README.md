# Score OS — Colosseum Arena Preview (not live)

Interactive homepage hero: 3D Colosseum carousel for Score OS.

- **Preview only.** Live site untouched: https://scoresos.com
- `noindex` / `robots.txt` / `X-Robots-Tag` — do not index
- Engine: getlayers Carousel Spotlight (CSS 3D concave ring), restyled as a Roman arena
- Features as arch-topped stone cards; CROA-safe copy (no outcome guarantees, no fake scores)

## URLs
- Colosseum (current root): `/` and `/colosseum/`
- Prior Championship HQ concept: `/championship/`
- getlayers Carousel Spotlight original: `/original/`
- Same layer, light Score OS brand only: `/branded/`

## Local
```bash
python3 -m http.server 8765
# open http://127.0.0.1:8765/
```

- `/cards/` — Arsenal carousel with 16 prompt-extracted feature cards (neon green cinematic art). Keep `/branded-green/` as the approved baseline.

## Routes
- `/` colosseum / prior preview
- `/cards/` static feature cards
- `/video-cards/` same carousel with free looping cinematic clips on the front card + detail view

## Lead forms (video-cards preview)

- **Read Your Own Report eBook card** (`video-cards/index.html`, `#freebies`): HighLevel form ID `HGf6V7IAVpN83W1iz6eB` (Score OS add-ons HighLevel), form name **Read Your Own Report - Free eBook**. Embedded as an inline iframe plus `https://link.msgsndr.com/js/form_embed.js` (loaded once, end of body). Every submission emails the real eBook and creates a real lead, so do not test-submit it.
- The agency freebie card ("Free sample dispute letter pack") is still a placeholder with no backend.
