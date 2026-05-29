# What Pricing Pages Confess When Nobody's Watching

Talk deck for **The Product Folks · Chennai** (GrabChai meetup).
Speaker: Santhosh Guru.

**Live:** https://santhoshguru.github.io/tpf-pricing-talk/

## What this is
A single self-contained HTML slide deck (no build step, no framework). Open
`index.html` in any browser. Navigate with arrow keys / space / scroll; progress
bar on top, nav dots on the right.

## Structure
- `index.html` — the entire deck (HTML + CSS + JS inline). A `SLIDE INDEX` with
  per-slide code names is in the comment at the top of the file.
- `assets/` — screenshots, the two SVG diagrams, and a local copy of Chart.js
  (so the deck works fully offline).

## Editing
Each slide is one `<section class="slide">` with an id (e.g. `id="s05-basecamp"`).
Search the id to jump to a slide and edit it in isolation. To swap a screenshot,
replace the file in `assets/` (keep the same name). Colours live in the `:root`
CSS variables near the top.

## Deploy
Hosted on GitHub Pages from `main`. Push a change and it redeploys in ~1 minute.
