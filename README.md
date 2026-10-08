# Ethan Feldman — personal website

Static site, no build step.

- `index.html` — portfolio
- `resume.html` — printable resume
- `assets/` — headshot and level images

## Publish on GitHub Pages

1. Copy everything in this folder to the root of your repository (e.g. `EthanFeld/EthanFeld.github.io`, or an existing repo).
2. Commit and push.
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
4. The site goes live at `https://ethanfeld.github.io/` (user-site repo) or `https://ethanfeld.github.io/<repo-name>/`.

Keep the `assets/` folder next to `index.html`; the zoom section loads its images from there.
