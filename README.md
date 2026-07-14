# Coffee & Campaigns — hiremarketingexpert.com

Single-page portfolio experience. Vanilla HTML/CSS/JS. No build step, no framework.

## Upload to GitHub Pages

Upload EVERY file below to the **root** of the repo (not inside a folder):

```
index.html
CNAME
.nojekyll
assets/grid-coffee.jpg
assets/grid-diving.jpg
assets/grid-wedding.jpg
assets/grid-pilates.jpg
assets/og-image.png
```

Then: repo → Settings → Pages → Source: `main` branch, `/ (root)` → Save.

## Notes

- `assets/` must keep its exact folder name and filenames, or the case-study images will break.
- `CNAME` already contains hiremarketingexpert.com so the custom domain connects on deploy.
- `.nojekyll` stops GitHub from processing the site as a Jekyll blog. Do not delete it.
- Delete any old files still in the repo (old index.html, _config.yml, theme folders), or they will override this.
- Images only appear when index.html is opened alongside the assets folder. Opening index.html on its own will show blanks.
- After deploying, force social platforms to refresh the link preview: LinkedIn Post Inspector, Facebook Sharing Debugger.

## Contact CTA

All "Work With Me" buttons point to: zaida.zaman@icloud.com
