# Daria Bodaikina — Portfolio

Static one-page portfolio: hero intro, showreel, two product cases (App fintech, Payment system) and experience.
No build step and no dependencies — plain HTML, CSS and JavaScript. The Sora font loads from Google Fonts.

## Structure

```
index.html   the whole site, with the case pop-ups and animations inline
assets/      images and the showreel video used by the page
.nojekyll    tells GitHub Pages to serve the files as they are
```

## Preview locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Publish on GitHub Pages

1. Create a repository and push the contents of this folder to the `main` branch.
2. In the repository open **Settings → Pages**.
3. Under **Build and deployment** choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute the site is live at `https://<username>.github.io/<repository>/`.

All paths are relative, so the site works both at the root of a domain and in a sub-folder.
