# The Chicago Ten

A Jekyll site on GitHub Pages collecting archived sources on the Chicago Ten.

- **Content** is converted from Wayback Machine captures with
  [DeadHonestCitation](https://github.com/obrien-k/DeadHonestCitation) (`dhc`).
  Each source has a provenance-stamped citation in `_data/sources/<id>.yml`
  (extracted text in `_sources/<id>.md`), rendered with
  `{% include cite.html id="<id>" %}`.
- **Editing** happens at `/admin/`, which is
  [DeadSimpleCMS](https://github.com/obrien-k/DeadSimpleCMS). Drafts live in
  `_drafts/`, and publishing from the admin moves them to `_posts/`.
