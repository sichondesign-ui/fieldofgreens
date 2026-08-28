# Sichon Design × Field of Greens — Client Dashboard

Static site for GitHub Pages. `index.html` is the client-facing dashboard; every deliverable set lives in a dated folder under `deliverables/` so older versions are preserved.

## Structure

```
index.html                      ← dashboard (edit to add releases)
assets/                         ← logos
deliverables/
  2026-08-28/                   ← Release 01 (frozen — never edit)
    licensing-deck-before-after.html
    img/                        ← images for the before/after doc
    sitemap-v3.html
    wireframe-home.html
    journey-menu-order.html
    journey-licensing-inquiry.html
    journey-catering-ezcater.html
```

## Adding a release

1. Create `deliverables/YYYY-MM-DD/` and copy the new/updated files in. Never edit an existing dated folder.
2. In `index.html`, find the `RELEASE ARCHIVE` comment and paste a new `<section class="release">` block directly below it (newest stays on top).
3. Move the `Latest` badge to the new release and update the "Latest release" / "Deliverables to date" numbers in the hero.

## Publishing

Push this folder to a GitHub repo, then Settings → Pages → deploy from the main branch root. The dashboard will be live at `https://<user>.github.io/<repo>/`.
