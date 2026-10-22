# Carter Montag — academic website

A simple, responsive, accessible academic website, ready for GitHub Pages.
The site uses plain HTML, CSS, and a few lines of JavaScript, with no build tools, account credentials, analytics, or third-party assets.

## Preview locally

Open `index.html` in a web browser or, from this directory, run:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish on GitHub Pages

1. Sign in at https://github.com and create a **public** repository named `<YOUR_GITHUB_USERNAME>.github.io` (replace with your actual GitHub username; do not include angle brackets).
2. Upload the *contents* of this folder (`index.html`, `README.md`, `.nojekyll`, and the `assets/` folder) to the repository's **root**. Do not upload only the ZIP file.
3. Go to the repository's **Settings → Pages → Build and deployment**. Set **Source** to **Deploy from a branch**, select **main** and **/(root)**, then click **Save**.
4. Open `https://<YOUR_GITHUB_USERNAME>.github.io/` after GitHub completes the Pages deployment.

The site also works inside another repository (as a project site) because all asset paths are relative.

## Update content

- Edit text, links, and sections in `index.html`.
- Edit color, spacing, layout, and responsiveness in `assets/styles.css`.
- Replace `assets/Carter_Montag_CV.pdf` when the CV changes.
- Add your GitHub profile link if desired, and update presentations as new events occur.
- The CV included here is designed for a public website: it omits the phone number and corrects the descriptions of PhD and LLNL research. It does **not** claim to have established spectral transport or tested warm-start integration.

## Notes

This is public-facing academic content. Read everything before publishing; GitHub Pages sites are publicly accessible. The one-page design currently lists only presentations confirmed from the CV, not future or unconfirmed appearances. No custom domain is configured.
