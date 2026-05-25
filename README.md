# Dr. Kokoy Siti Komariah — Personal Website

A lightweight, single-file personal website with a "Claude Code" terminal/tech aesthetic.

## Files
- `index.html` — the entire website (photo is embedded, no image files required)
- `Kokoy_Siti_Komariah_CV.pdf` — linked by the "Download CV" buttons
- `profile.jpg` — your optimized photo (optional; already embedded in index.html)

## Host on GitHub Pages (free, ~2 minutes)
1. Create a new public repository named **`<your-username>.github.io`**
   (e.g. `kokoysk.github.io`).
2. Upload `index.html` and `Kokoy_Siti_Komariah_CV.pdf` to the repo
   (Add file → Upload files → Commit).
3. Go to **Settings → Pages**, set **Source = Deploy from a branch**,
   branch **`main`**, folder **`/ (root)`**, then Save.
4. Wait ~1 minute. Your site is live at `https://<your-username>.github.io`.

> Tip: keep `index.html` and the PDF in the same folder so the CV download link works.

## Easy things to edit (open index.html in any text editor)
- Email: search for `kokoy.sitikomariah@gmail.com` and replace.
- Profile metrics: search for `data-count` to update numbers.
- Add a publication: edit the `PUBS` array near the bottom of the file.
- Replace photo: re-encode a new image to base64 and swap the `src="data:image/jpeg;base64,..."` value on the `.avatar` image.
