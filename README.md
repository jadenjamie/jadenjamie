# Academic personal website — quick setup

This is a traditional, simple academic-style website. No installation, programming tools, or paid services needed.

## Edit the site
1. Open `index.html` in a text editor and replace `Your Name`, the sample bio, project titles/descriptions, and `YOUR-USERNAME` URLs.
2. Add your resume PDF as `resume.pdf` in the same folder as `index.html`.
3. Add your headshot as `headshot.jpg` in the same folder, then change `src="profile.svg"` to `src="headshot.jpg"` in `index.html`.
4. Edit `photos.html` with your own pictures and captions. Example: Replace `<div class="photo-placeholder">Your photo here</div>` with `<img src="photo1.jpg" alt="Caption describing photo">` and upload `photo1.jpg` to the same folder.
5. Open `index.html` in your web browser to preview locally.

## Publish on GitHub Pages for free
1. Create / sign in to your GitHub account.
2. Create a **public** repository named exactly `YOUR-GITHUB-USERNAME.github.io` (replacing with your actual username).
3. Upload `index.html`, `photos.html`, `style.css`, `profile.svg`, and your added PDF/images **directly into the repository root**, not into an extra nested folder.
4. In repository **Settings → Pages → Build and deployment**, set **Source: Deploy from a branch**. Select `main` and `/(root)`, then Save.
5. Your site will appear at `https://YOUR-GITHUB-USERNAME.github.io` after publishing completes (sometimes this takes a few minutes).

If you see a 404 initially, make sure the homepage is named `index.html` and that Pages is deploying from `main` / `(root)`.

GitHub Docs: https://docs.github.com/en/pages/quickstart
