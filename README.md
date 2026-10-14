# SoFlo Cinema Club

Static site for SoFlo Cinema Club. A single `index.html` with inline CSS, so there is no build step.

## Deploy on GitHub Pages

1. Create a new repo (for example `soflocinemaclub`) and add `index.html` and this README.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Custom domain (optional)

Add a `CNAME` file containing the domain, or set it under Settings → Pages, then point DNS at GitHub Pages.

## Editing

- Links live in the two `.tickets` sections of `index.html`.
- Colors are the CSS variables at the top of the `<style>` block.
- To add a logo, drop `logo.png` in the repo and add `<img src="logo.png" alt="SoFlo Cinema Club" width="120">` above the `<h1>`.
