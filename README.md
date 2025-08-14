# Mesa Digital Angola — Demo (GitHub Pages)

This repository hosts a **single-file** demo app for QR ordering (Customer QR, Kitchen, Floor, Admin).

## How to publish on GitHub Pages (Project Pages)

1. Create a new repo on GitHub (e.g., `mesa-digital-amostra`).
2. Upload these three files to the **root** of the repo:
   - `index.html`
   - `README.md`
   - `.nojekyll`
3. Commit.
4. In the repo, go to **Settings → Pages**.
5. Under **Source**, choose **Deploy from a branch**. Select your default branch (e.g., `main`) and **/ (root)**.
6. GitHub Pages will publish your site; the public URL will look like:
   - `https://<your-username>.github.io/mesa-digital-amostra/`

> If you use a user/organization site (repo name `your-username.github.io`), the URL will be the root domain.

## Notes
- The app is a static site (no build step).
- `.nojekyll` disables Jekyll so files are served as-is.
- All state is in `localStorage` in the browser.
