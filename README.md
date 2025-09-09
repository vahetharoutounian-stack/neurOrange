# neurOrange — GitHub Pages Starter

This repository is pre-configured to host your iPhone-friendly neurOrange web app on **GitHub Pages**.

## Quick Start (No Terminal)

1. Create a new repo on GitHub (Public).  
2. Upload these files (drag‑and‑drop the whole folder):
   - `index.html` (launcher)
   - `neurOrange.html` (replace with your real app HTML)
   - `assets/neurOrange_icon_180.png`
   - `favicon.png`
   - `site.webmanifest`
   - `.nojekyll`
   - `404.html`
3. Go to **Settings → Pages**:  
   - **Source:** Deploy from a branch  
   - **Branch:** `main` (or `master`) / **Folder:** `/ (root)`  
4. Wait for the deployment link, then open it in Safari and **Add to Home Screen**.

### Notes
- iOS home screen uses the icon specified by `<link rel="apple-touch-icon" href="assets/neurOrange_icon_180.png">`.
- `index.html` redirects to `neurOrange.html`. Replace `neurOrange.html` with your actual app.
- `.nojekyll` ensures GH Pages serves assets under `assets/` without Jekyll processing.
- `site.webmanifest` improves installability on Android/modern browsers.
