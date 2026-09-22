# Nathan Swanner Portfolio — GitHub Pages Build

This folder is ready to publish directly from the **root of the `main` branch** on GitHub Pages.

## Important

Upload the **contents of this folder**, not a ZIP file and not an enclosing `nate-portfolio` folder. At the top level of the GitHub repository you should be able to see:

- `index.html`
- `styles.css`
- `script.js`
- `CNAME`
- `.nojekyll`
- `404.html`
- `assets/`
- `case-studies/`

The `case-studies/` folder contains both legacy `.html` files and clean directory-based routes. The homepage uses the clean routes, for example `case-studies/portfolio-operations/`.

## GitHub Pages settings

In the repository go to **Settings → Pages**. Under **Build and deployment** choose **Deploy from a branch**, then select **main** and **/(root)**. The custom domain should be `nateswanner.com`.

The included `CNAME` file preserves the custom domain when publishing from a branch. The included `.nojekyll` file tells GitHub Pages to serve this static HTML/CSS/JS site directly.
