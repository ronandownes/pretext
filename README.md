# School Mathematics — PreTeXt source collection

This repository is intended to preserve the source of five open PreTeXt textbooks by Katherine Yoshiwara and collaborators, as the foundation for a future unified Irish school mathematics book.

## Sources

- [Core Mathematics](https://github.com/byoshiwara/core-math)
- [Elementary Algebra](https://github.com/byoshiwara/elem-alg)
- [Intermediate Algebra](https://github.com/byoshiwara/int-algebra)
- [Modeling, Functions, and Graphs](https://github.com/byoshiwara/mfg)
- [Trigonometry](https://github.com/byoshiwara/trig)

The GitHub Actions workflow in `.github/workflows/import-and-publish.yml` retrieves the five original repositories, retaining their licence and copyright files, records the upstream revision for each, commits them under `sources/`, builds their individual PreTeXt HTML outputs, and publishes a collection landing page to the `gh-pages` branch.

The initial website is **not yet a single editorially merged PreTeXt textbook**. It is an initial unified subject entry point to the individual books, which will be integrated later. Read `site/build-status.txt` in the built site for build outcomes.

Original authors retain the copyright to their works. Review each source directory's licence and attribution before redistributing adapted material. Do not assume that all assets necessarily share an identical licence.

## GitHub Pages

This repository may need **Settings → Pages → Build and deployment → Deploy from a branch → gh-pages / (root)** selected by the repository owner. The site will then be at:

https://ronandownes.github.io/pretext/

If any source build fails, its original PreTeXt source still remains available under `sources/` after the import has succeeded.
