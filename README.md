# Trading the Joint — Manifest 2026

Slides for an informal Manifest 2026 talk on statistical arbitrage over
prediction markets: rebuilding the joint distribution that a pile of
related markets are marginals of, sampling from it, and trading the
inconsistencies.

**Live deck:** <https://evand.github.io/manifest-2026-talk/>
**Live forecast it embeds:** <https://evand.github.io/2026-senate-forecast/>

## Presenting

- Single static page (reveal.js from CDN). Needs network for the CDN,
  fonts, and the two live-demo iframe slides.
- `S` opens speaker view (notes + timer). `F` fullscreen. `Esc` overview.
- Slides 5 and 16 embed the live forecast site; if venue wifi dies, the
  "open in new tab" links below each embed are the fallback.

## Editing

Everything is in `index.html`. Test locally:

```bash
python -m http.server 8080   # then http://localhost:8080
```

## Credits

Talk by Evan Daniel. Deck researched, written, and deployed by Claude
(Opus 4.8) from a one-paragraph brief — drawing on a year of shared
project notes. Earthrise photo: NASA, Apollo 8 (public domain).
Flag meme: the internet's.
