# rumath-prog2

[日本語](./README.ja.md) | English

Course site for "Programming and Exercises 2" (C language) at Ryukoku University,
Department of Mathematical Sciences and Informatics.

## Course site

Published with GitHub Pages: **<https://sanoakr.github.io/rumath-prog2/>**

The site is built from `docs/` with [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
and deployed by `.github/workflows/pages.yml` on every push to `main`.
Pages for each week are added as the course progresses. Setup guides shared with the
sister course ([rumath-network](https://github.com/sanoakr/rumath-network)) live here.

```fish
uv sync                 # install mkdocs-material
uv run mkdocs serve     # preview at http://127.0.0.1:8000/rumath-prog2/
```
