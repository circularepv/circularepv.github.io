# CIRCULARePV website

Static website for **CIRCULARePV -- Data-Driven Circularity for Reused Photovoltaic Modules**.

## Files

- `index.html` - website content
- `styles.css` - layout, colours and responsive styling
- `script.js` - mobile navigation
- `assets/circularepv-logo.png` - project logo

## Publish on GitHub Pages

Upload all files and the `assets` folder to the root of the `circularepv` repository.

GitHub Pages should be configured as:

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

The site will then appear at:

`https://joaogabrielbessa.github.io/circularepv/`

## Easy edits

Most text can be changed directly in `index.html`.
Colours are defined at the top of `styles.css`.


## Version 2 edits

The team section now contains three photo placeholders.

To add a photograph, place the image in `assets/`, then replace the corresponding `portrait-placeholder` div in `index.html` with an image tag. Example:

`<img src="assets/joao-bessa.jpg" alt="João Gabriel Bessa">`

The LinkedIn/Lattes buttons currently use `href="#"` because the profile URLs were not supplied. Replace `#` with the real public profile URL.

Host links, CORDIS and the project email are already configured.
