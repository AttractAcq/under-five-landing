# Under Five

Landing page for Under Five, a human-operated lead response service. The page is a single static file, `index.html`, and this repo is set up to publish it with GitHub Pages.

## Preview locally

From the repository root:

```bash
python3 -m http.server 43117
```

Then open [http://127.0.0.1:43117](http://127.0.0.1:43117).

## Deploy

Pushes to `main` run `.github/workflows/pages.yml`, which publishes `index.html` to GitHub Pages.

The repository must use GitHub Actions as its Pages source (Settings → Pages → Build and deployment → Source: GitHub Actions). The site is then served at:

https://attractacq.github.io/under-five-landing/

`.nojekyll` is included so Pages serves the HTML as-is and does not run it through Jekyll.
