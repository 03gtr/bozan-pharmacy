# BOZAN PHARMACY — Smart Business Card

One-page mobile-first website for BOZAN PHARMACY.

## Files
- `index.html` — complete website
- `assets/bozan-logo.jpg` — supplied pharmacy logo

## Deploy on GitHub Pages
1. Upload `index.html` and the `assets` folder to the repository.
2. Commit to the `main` branch.
3. GitHub → Settings → Pages.
4. Select `Deploy from a branch`.
5. Select `main` and `/ (root)`.
6. Save.

## QR behavior
The QR code is generated from `window.location.href`, so it points to the final deployed page URL automatically.

Note: the QR generator library is loaded from cdnjs. If you want a fully offline/no-CDN version, replace it with a local QR library.
