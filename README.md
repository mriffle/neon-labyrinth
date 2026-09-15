# Neon Labyrinth — product site

**Live site: https://mriffle.github.io/neon-labyrinth/**

This repository is the GitHub Pages deployment of the product site for
[Neon Labyrinth](https://channelstore.roku.com/details/39aa4c5de37344ee05259c62be5ec49a:de59420438a7e2c38c61f63bbaf37e4d),
a neon maze screensaver for Roku devices. It is a static site: plain HTML,
CSS, and a small canvas demo of the maze generator and solver, with no build
step and no third-party scripts, fonts, or analytics.

## This repo is a published snapshot

The site is authored in the (private) product repository alongside the
screensaver's source, and mirrored here by a deploy script. `main` holds a
single commit: the latest snapshot of that source directory, labelled with
the source commit it came from; earlier snapshots are not retained. The
demo script `maze.js` is published minified; its readable source stays in
the product repo. **Changes made directly in this repository are
overwritten by the next deploy**, so edits belong in the product repo.

Pages serves the `main` branch from the repository root.

## Pages

- `index.html` — landing page with the live maze demo
- `support.html` — setup, settings, troubleshooting, release notes
- `privacy.html`, `terms.html` — privacy policy and terms of use
- `img/` — screenshots captured on a Roku Ultra, resized for the web

## Contact

neonlabyrinth@ogdb.com

Roku is a trademark of Roku, Inc. This product is not affiliated with or
endorsed by Roku, Inc.
