# Yiyun Chen — personal academic website

A dependency-free static website for GitHub Pages, based on the supplied CV and visual reference.

## Preview

Open `index.html` in a browser, or run `python3 -m http.server 8080` in this folder.

## Add your portrait

Save your photo as `assets/portrait.jpg`. In `index.html`, replace the `<div class="portrait" ...>...</div>` with:

```html
<img class="portrait" src="assets/portrait.jpg" alt="Yiyun (Nicole) Chen" style="object-fit:cover">
```

## Publish on GitHub Pages

1. Create a public repository named `niccChen.github.io` under the `niccChen` account.
2. Upload the **contents** of this folder to the repository root (`index.html`, `style.css`, `.nojekyll`, and `assets/` when populated).
3. Open repository Settings → Pages. Select “Deploy from a branch”, branch `main`, folder `/ (root)`, then Save.
4. After GitHub completes deployment, the expected URL is `https://niccchen.github.io/`.

The address above is a deployment target, not a verified live site. If the repository already exists, merge these files into it rather than replacing unrelated content.

## Content notes

- Research review statuses and results reflect the supplied CV; update them when statuses change.
- Affiliation and self-introduction are on the first screen, followed by News, Education, and navigation cards. Research and project cards link to independent detail pages.
- Locally hosted DM Sans and Lora typefaces are licensed under the SIL Open Font License; see assets/fonts/.
- The portrait is a visible placeholder until a photo is supplied.
- No phone number, resume download, invented paper links, or unverified Scholar profile is published.
- All asset references are relative, so the site can also be hosted under a repository subpath.
