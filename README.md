# crypto-quiz

This repository contains a single static quiz page: `DESquiz.html`.

Why I added `index.html`
- GitHub Pages serves a default file at the site root. If there's no `index.html` (or correct casing), visiting the root URL can produce a 404. To avoid that, an `index.html` redirect was added to forward visitors to `DESquiz.html`.

How to test locally

Using Python 3 (bundled on many systems):

```powershell
python -m http.server 8000; # then open http://localhost:8000/
```

Using Node.js (with npx):

```powershell
npx serve -s . -l 8000; # then open http://localhost:8000/
```

After verifying locally, commit and push the change. Ensure GitHub Pages is configured to serve from the `main` branch and the root folder.

If you'd like, I can also add a small GitHub Actions workflow to auto-deploy or check the Pages configuration.
