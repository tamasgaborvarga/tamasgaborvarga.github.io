# Tamás Gábor Varga — Portfolio

Personal one-page portfolio. Static site (single `index.html`, no build step).

**Live:** https://USERNAME.github.io/

## Files
- `index.html` — the whole site
- `worldcup.jpg`, `holdudvar.jpg` — project cover images
- `og-image.png` — social share preview (1200×630)
- `cv.pdf` — downloadable CV
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy (GitHub Pages — user site)
1. Create a repository named exactly **`USERNAME.github.io`** (replace `USERNAME` with your GitHub username).
2. Upload all files in this folder to the repository root.
3. The site goes live at `https://USERNAME.github.io/` within a minute.

## After deploy
Set the absolute URL for the social preview image in `index.html` (`og:image` and
`twitter:image`) to `https://USERNAME.github.io/og-image.png` so LinkedIn/Facebook
render the preview reliably.
