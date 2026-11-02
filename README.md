# PlayDSA website

Static site for PlayDSA: landing page, how-to-use guide and privacy policy. Plain HTML + CSS, no build step, no tracking.

| File | Page |
|---|---|
| `index.html` | Landing page |
| `how-to-use.html` | How to use the app |
| `privacy.html` | Privacy policy (use this URL in Google Play Console) |
| `style.css` | Shared styles |
| `assets/icon.png` | App icon |

## Publish on GitHub Pages

1. Create a new public repository on GitHub, e.g. `playdsa`.
2. Upload every file in this folder (including the hidden `.nojekyll` file) to the root of the repo.
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute the site is live at `https://<your-username>.github.io/playdsa/`.
5. In Google Play Console, set the privacy policy URL to `https://<your-username>.github.io/playdsa/privacy.html`.

## Before launch

- Replace the two `href="#get"` links in `index.html` (search for "Replace href") with your Google Play listing URL.
