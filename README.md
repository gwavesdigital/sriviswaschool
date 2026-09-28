# Sri Viswa School – Palakollu | School Connect

Bilingual (English + తెలుగు) school website with Teacher Portal & Principal Desk.

## 🚀 Deploy on GitHub Pages

1. Create a GitHub repo (public).
2. Upload these files to the repo root:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `README.md`
   - `assets/` folder (see below)
3. Go to **Settings → Pages** → Source: **main branch / root** → Save.
4. Your site goes live at: `https://<your-username>.github.io/<repo-name>/`

## 📸 Assets to Upload (REQUIRED)

Place inside `assets/` folder:

| File | Purpose | Recommended |
|---|---|---|
| `logo.png` | Used in navbar, hero, poster, seal | 512×512 PNG |
| `favicon.png` | Browser tab icon | 64×64 PNG |
| `school-entrance.jpg` | Hero background photo | 1920×1080 JPG |
| `icons/icon-192.png` | PWA icon small | 192×192 PNG |
| `icons/icon-512.png` | PWA icon large | 512×512 PNG |

If any file is missing, the site shows a gold "SV" fallback — nothing breaks.

## 🔐 Principal Desk Password

Default: **`2026`**
To change it, edit this line in `index.html`:
```js
const PRINCIPAL_PASSWORD = "2026";
