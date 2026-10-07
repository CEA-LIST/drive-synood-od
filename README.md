# Drive-SynOOD-OD project page (`gh-pages` branch)

This branch holds only the project website, served by GitHub Pages at
<https://cea-list.github.io/drive-synood-od/>. The code lives on the `main` branch.

- `index.html`: the whole page.
- `static/css/`: Bulma 0.9.4 (MIT License) and `site.css`.
- `static/fonts/`: Inter (SIL Open Font License 1.1, see `OFL-Inter.txt`).
- `static/images/`: figures.

Plain static HTML with no build step; `.nojekyll` tells GitHub Pages to serve the files as they are.
To preview locally, run `python3 -m http.server` in this directory and open <http://localhost:8000>.
