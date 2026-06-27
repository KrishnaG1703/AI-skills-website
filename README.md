# Krishna Ganga L — AI Portfolio (CalPro)

A single-page AI portfolio that showcases your ML/AI skills and your app **CalPro**.

## Open it
Just double-click **`index.html`** — it runs in any modern browser, no build step or internet required
(an internet connection only makes the Google font crisper; it falls back gracefully offline).

## What's inside
```
index.html              ← the whole site (HTML + CSS + JS, self-contained)
assets/
  avatar.webp           ← your Pixar-style avatar (front-facing) — used on the site (32 KB)
  avatar-alt.webp       ← three-quarter-angle alternate (swap if you prefer)
  avatar*.png           ← full-resolution PNG originals (kept locally; not pushed to the repo)
  shots/                ← all 11 CalPro screenshots (.webp)
```

## Easy tweaks
- **Swap the avatar:** rename `avatar-alt.webp` → `avatar.webp` (back up the current one first).
- **LinkedIn link:** in `index.html`, search for `linkedin.com/` and paste your full profile URL.
- **Email:** search for `krishna091718@gmail.com` and adjust if needed.
- **Colors:** all theming lives in the `:root { ... }` block at the top of the `<style>` — `--amber` is the main accent.
- **Side margins:** the centered column is `width: 70%` (15% free each side) via the `.wrap` rule.

## Design notes
- Visual language mirrors CalPro: warm amber on near-black, glass cards, progress-ring accents.
- Subtle 3D: mouse-tilt cards, a floating avatar, tilted phone mockups, scroll-reveal — all respect
  `prefers-reduced-motion`.
- Fully responsive; the layout stacks to a single centered column on tablet/mobile.
