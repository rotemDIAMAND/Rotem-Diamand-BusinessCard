# Rotem Diamand — Digital Business Card

A personal digital business card built with **HTML & CSS only** (no JavaScript),
as required by the assignment.

## Files

- `index.html` — redirects to `light.html` (so GitHub Pages has a root page)
- `light.html` / `dark.html` — the two theme versions of the card, cross-linked
- `style.css` — shared layout/structure (theme-independent)
- `light-theme.css` / `dark-theme.css` — color palettes as CSS variables

The light/dark toggle is implemented as a link between two static HTML pages
that share the same layout but load a different theme stylesheet — no
JavaScript involved.

## How to publish on GitHub Pages

1. Create a **public** repository, e.g. `rotem-diamand-business-card`.
2. Push all files in this folder to the repo root (`git add . && git commit -m "Business card" && git push`).
3. In the repo: **Settings → Pages → Branch: main → / (root) → Save**.
4. Wait a minute, then your site will be live at:
   `https://<your-github-username>.github.io/<repo-name>/`

## Note on content

Per the assignment instructions, the profile photo is a generated placeholder
avatar and the phone number is fabricated — only the name, GitHub link, and
email were provided as real details.
