# Alexander Shaw independent portfolio

Static website for a new, separate GitHub Pages repository. No build dependencies.

## Publish
Create a new repository named `alex-shaw-consulting` in the personal GitHub account. Upload this folder’s contents to its root (including `.nojekyll`). In Settings → Pages, select Deploy from a branch, `main`, `/ (root)`. The expected project URL is `https://alexandershaw4.github.io/alex-shaw-consulting/` once deployment succeeds. This is an expected URL, not a confirmed live deployment.

No custom domain is configured. Do not copy the CPNS CNAME. The existing CPNS site is untouched.

## Local preview
Run `python3 -m http.server 8000` in this folder, then open http://localhost:8000.

Contact: alexandershaw4@gmail.com. Homepage text and styling are in `index.html` and `assets/style.css`. The CNS service page is `cns-modelling.html`. Demos and media are served locally within this project; MathJax loads from its existing CDN where required.
