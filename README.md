# slides

Presentation slides for talks, demos, and workshops about UIPS Browser Kit,
built with [reveal.js](https://revealjs.com/).

## Structure

```
slides/
  talks/        ← conference and community talks (one subfolder per event)
  workshops/    ← hands-on workshop decks (one subfolder per workshop)
  demos/        ← short demo decks shown during releases or onboarding
  assets/       ← shared images, logos, and CSS theme overrides
```

Each deck lives in its own subfolder with a self-contained `index.html`
(reveal.js loaded from CDN or vendored locally).

## Conventions

- Folder name: `YYYY-<slug>` for dated talks, plain `<slug>` for evergreen decks.
- Every deck folder contains at minimum `index.html` and a `README.md`
  describing the talk, target audience, and event.
- Shared assets go in `assets/`; do not duplicate logos per-deck.

## Serving locally

```bash
npx serve talks/YYYY-<slug>
# open http://localhost:3000
```

## License

Content: [Apache 2.0](LICENSE)
