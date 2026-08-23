# RiftCity Safe Minigame Lab — Audited Build 2

This build is intentionally a **single-file GitHub Pages prototype**.

## Upload
Upload `index.html` to the root of the repository. `README.md` is optional.

Then go to GitHub **Settings → Pages → Deploy from a branch → main → /(root)**.

## Why single-file?
The previous build used separate `app.js` and `style.css` files. That is valid, but replacing a Pages prototype can sometimes leave old browser/CDN-cached assets while the new HTML is already live. This build embeds all CSS and JavaScript directly in `index.html`, eliminating that mismatch.

Modes included:
1. Manual Dial
2. Tumblers
3. Sound Wave
4. Rotating Rings
5. Electronic Route
6. Listen & Stop
7. Deduction
