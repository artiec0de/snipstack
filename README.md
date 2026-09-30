# SnipStack

A tiny PicSay-style photo editor that runs in the browser. One HTML file, no build step, no dependencies.

## What it does

- **+ Photo**: the first photo becomes the background (canvas size = that photo). Later photos go on top as layers.
- **Cut**: draw around the part you want to keep (lasso). Tick *Keep original* to leave the source photo in place.
- **Erase**: rub out leftover edges with an adjustable brush.
- **Move**: drag to move, pinch to resize and rotate, or drag the yellow corner handle. Precise **Size** / **Turn** sliders plus Fit, Fill, ½, 2×, Straighten and Center buttons.
- **Layers**: reorder, flip, copy, delete.
- **Undo**: last 40 steps.
- **Save**: exports a PNG at the background photo's resolution (photos are capped at 2000 px on the long side).

## Run it on your phone (GitHub Pages)

1. Push these files to a GitHub repo.
2. Repo → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. Open `https://<your-username>.github.io/<repo-name>/` on your phone.
4. In Chrome: ⋮ menu → **Add to Home screen** / **Install app**. It opens full-screen like a normal app.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole app: markup, styles and script |
| `manifest.webmanifest` | Lets Android install it to the home screen |
| `icon-192.png`, `icon-512.png` | App icons |

## Notes

- HEIC photos may not open in Chrome; use JPG or PNG.
- Everything happens on the device. Nothing is uploaded anywhere.
