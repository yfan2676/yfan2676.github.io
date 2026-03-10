# yfan2676.github.io

This site is set up as a lightweight GitHub Pages / Jekyll site so the publications list
can be generated automatically from files in `_publications/`.

## Add a publication

1. Copy `_publications/template/` to a new folder in `_publications/`.
2. Edit the front matter in the new folder's `index.md`.
3. Replace `teaser.svg` with your own teaser figure if needed.
4. Commit and push. GitHub Pages will rebuild the homepage and include the new entry.

Each publication entry is rendered from:

- `title`
- `slug`
- `authors`
- `venue`
- `status`
- `year`
- `date`
- `teaser`
- `links`
