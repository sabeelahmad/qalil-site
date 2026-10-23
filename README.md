# qalil-site

The website for [Qalil](https://qalil.app), an iPhone app for reading a little Quran every day. Served by GitHub Pages from `main` at https://qalil.app.

Plain HTML and CSS, with no build step, no JavaScript, no trackers and no external requests.

| Path | Page |
| --- | --- |
| `index.html` | Home |
| `privacy/index.html` | Privacy policy: https://qalil.app/privacy/ |
| `support/index.html` | Support, FAQ and credits: https://qalil.app/support/ |
| `404.html` | Not found |

- `assets/site.css`: all styles. Colours match the app (dark only).
- `assets/fonts/`: Inter 200, 300 and 300 italic, subset to Latin as woff2 (SIL OFL 1.1, see `Inter-OFL.txt`).
- `assets/img/`: `logo.svg`, `lockup.svg` and `icon-1024.png` copied from the app's `assets/brand/`; `og.png` (1200×630) is the lockup on the base colour; `apple-touch-icon.png` and `favicon-32.png` are resized from `icon-1024.png`.
- `CNAME`: the custom domain. `.nojekyll`: serve the files as they are.

To preview locally: `python3 -m http.server 8000`, then open http://localhost:8000.

**Changing the privacy policy:** update the "Effective" date and add a line under "Changes to this policy" with the date and what changed. Publish it before the app version that needs it.
