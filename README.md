# Link Website

A single-page link hub that collects all my social links in one place.

- `index.html` holds the HTML, CSS and JS, with no build step. The avatar is in `images/` and the self-hosted Inter font in `fonts/`, so the page makes no requests to other sites.
- Links open in a new tab.
- Custom eggplant cursor. Left-clicking sets off a small burst of white sparkles that falls away. The burst is off for reduced-motion users.

## Editing links

Find the `<ul>` in `index.html` and change each `href` and label.

## Hosting

Any static host works. On GitHub Pages: Settings → Pages → deploy from the `main` branch, root folder.
