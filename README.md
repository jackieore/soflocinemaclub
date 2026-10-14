# SoFlo Cinema Club

Static site for SoFlo Cinema Club. A single `index.html` with inline CSS, so there is no build step.

**Status:** prototype. It's hosted on GitHub Pages for now and may move to a permanent home later.

**Live site:** https://jackieore.github.io/soflocinemaclub/

## Files

- `index.html`: the whole site (markup and CSS).
- `ticket.png`: the ticket graphic shown above the title.
- `.nojekyll`: tells GitHub Pages to serve the files as-is, without Jekyll.
- `.gitignore`: keeps local files like `.DS_Store` and `.claude/` out of the repo.

## Deploying

The site is deployed from the `main` branch, root folder, through GitHub Pages (Settings → Pages). Pushing to `main` redeploys it, usually within a minute or two.

```sh
git add -A
git commit -m "Describe the change"
git push
```

## Custom domain (optional)

Add a `CNAME` file containing the domain, or set it under Settings → Pages, then point DNS at GitHub Pages.

## Editing

- Links live in the two ticket sections of `index.html` (`#connect` and the group chats section).
- Colors are the CSS variables at the top of the `<style>` block.
- To swap the hero image, replace `ticket.png` (keep the same name) or change the `src` on the `.ticket-img` tag.

## Moving to a permanent home

Everything is plain files, so the site can move to any static host (another GitHub account or org, Netlify, Cloudflare Pages, or your own server). Copy `index.html` and the image files, then update any links that point at the old `github.io` URL.
