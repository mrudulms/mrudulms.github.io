# Personal academic website — M. S. Mrudul

A single-file website (`index.html`) ready for GitHub Pages. No build step, no Jekyll.

## Publish it (about 5 minutes)

1. Sign in to GitHub and create a **new public repository** named exactly
   `<your-username>.github.io` (for example `mrudulms.github.io`).
2. Upload these files to the repository root (Add file → Upload files):
   - `index.html`
   - `photo.jpg` — your portrait (a 5:6 portrait crop works best, about 400×480 px)
   - `cv.pdf` — your compiled CV
3. Commit. Then open **Settings → Pages**, set *Source* to **Deploy from a branch**,
   branch **main**, folder **/ (root)**, and save.
4. After a minute or two the site is live at `https://<your-username>.github.io`.

If `photo.jpg` is missing, the page shows an “MSM” monogram instead, so nothing breaks.
The **Download CV** button needs `cv.pdf` to be present.

## Things to update

- **npj Quantum Materials 11, 25 (2026)**: the CV has a placeholder DOI (`10.1038/XXXXX`),
  so this entry has no link yet. Wrap the title in `<a href="https://doi.org/...">…</a>`
  once you have the real DOI.
- **J. Phys. B (2026)** links to the arXiv version; swap in the journal DOI when it’s out.
- **Teaching**: the CV’s teaching record is still a placeholder, so the site lists only
  courses you can teach. Add TA/lecture experience under the “Teaching” section when ready.
- **New papers**: copy an existing `<li>` in the publication list. Add `data-first` for
  first-author papers and `data-selected` for highlighted ones, then update the counts
  on the three filter buttons.

## Notes

- Light and dark mode follow the visitor’s system setting.
- Your phone number is deliberately left off the public page.
- Fonts (Spectral, IBM Plex Sans) load from Google Fonts, with system fallbacks.
