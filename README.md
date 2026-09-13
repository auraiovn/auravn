# AURA Complete HTML Website

This package contains the website code AND every local image, video, audio and Virtual Try On garment asset referenced by the code.

## Important folder rule
Keep the `assets` folder beside `index.html`. Do not upload only the HTML files. The expected structure is:

```
index.html
about.html
categories.html
product.html
blog.html
...
assets/
  styles.css
  app.js
  tryon.js
  campaign-hero.webp
  ...
```

## Deployment
Upload the entire contents of this folder to the web root for `aura.io.vn`. The included `CNAME` contains `aura.io.vn`. Camera access requires HTTPS or localhost.

## Assets
See `assets/manifest.json` for the exact files referenced by the code. All referenced local assets were checked at build time.

## Fonts
Anton and Poppins are loaded from Google Fonts with system fallbacks in CSS. Font files are not bundled locally.

Build audit result: 0 missing referenced local assets.


HD campaign assets regenerated on 2026-09-13 to replace low-resolution crops.
