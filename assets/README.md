# Madera Quarry (Adkins Mountain) — static site for GitHub Pages

This repo contains a single‑page website that documents the history of the **Madera Quarry** at ~**37.14824, −119.79907** (PLSS: **Sec. 16 T9S R20E MDM**) in **Madera County, CA**.

## How to host on GitHub Pages

1. Create a new repo on GitHub (e.g., `madera-quarry-site`).  
2. Add these files at the root of the repo (keep the `assets/` folder next to `index.html`).  
3. Commit & push.  
4. In **Settings → Pages**, choose **Deploy from Branch**, and set **Branch: `main`**, **Folder: `/ (root)`**.  
5. Wait for the “Your site is live” banner; the URL will be `https://<your-username>.github.io/madera-quarry-site/`.

## Notes

- All sources are hyperlinked from the **Sources** section in `index.html`.  
- The “Kingsland Gray / Federal Office Building” ad is included via a **Wikimedia Commons** file with **no known copyright restrictions**.  
- Images from **Stone Quarries & Beyond** and **Calisphere** are *linked* (not embedded) to respect their rights statements. If you secure permission, you can add images to `/assets/` and update the Gallery section.

## Local preview

Double‑click `index.html` or serve locally with Python:

```bash
python3 -m http.server 8000
```

Then browse to <http://localhost:8000>.

---

MIT‑licensed content & code in this repo (except third‑party images/media linked via external URLs).