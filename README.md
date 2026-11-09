# Eco Step Flooring — Clone

A static mirror of [ecostep-six.vercel.app](https://ecostep-six.vercel.app/), with all assets
(images, video, fonts, CSS, JS) downloaded locally and served from this repository's subpath.

Live: https://ari-builds.github.io/ecostep-clone/

## Structure

```
index.html      # single page, anchor navigation
styles.css
script.js
hero.mp4
logo-transparent.png
images/         # locally mirrored Unsplash assets
```

## Hosting notes

Asset references are root-absolute and prefixed with `/ecostep-clone/` so the site works as a
GitHub Pages *project* site. Deployment is handled by `.github/workflows/deploy.yml`.
