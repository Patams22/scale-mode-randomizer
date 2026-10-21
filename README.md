# Music Theory Randomizer

A lightweight GitHub Pages web app for practicing:
- random root notes
- random scale degrees
- the resulting scale note
- the mode associated with that degree
- matching fretboard diagrams

## Included modal diagrams
The site already includes these user-supplied diagram images in `images/`:
- `ionian.png`
- `dorian.png`
- `phrygian.png`
- `lydian.png`
- `mixolydian.png`
- `aeolian.png`
- `locrian.png`

## Publish on GitHub Pages
1. Create a new public GitHub repository (for example `music-theory-randomizer`).
2. Upload **all files and folders** from this package to the root of the repository.
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then save.
6. Wait a minute or two for deployment.
7. Your site will appear at:
   `https://YOUR-USERNAME.github.io/music-theory-randomizer/`

## Replacing diagrams later
If you ever want to swap out a mode image, keep the same filename and upload the replacement to `images/`.

## Optional root-specific diagrams
You can optionally add files like `images/d-phrygian.png` or `images/bb-dorian.png`.
The app checks for a root-specific diagram first, then falls back to the generic mode image.
