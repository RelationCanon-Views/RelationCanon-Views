# RelationCanon-Views Project Page

Static, anonymized project page for *Relation-Conditioned Canonical Views
for Per-Hop Compositional Spatial Reasoning over 3D Gaussian Splatting
Scenes* (project alias **RelationCanon-Views**).

## Files

- `index.html` --- the page itself; pulls Bulma, FontAwesome, and Academicons
  from public CDNs.
- `static/css/style.css` --- minimal custom styles on top of Bulma.
- `static/images/` --- two figures lifted directly from the paper:
  `figure1_full.png` (paper Figure 1: two-hop primitive, *C<sub>r</sub>*
  canonical views, boundary-hard bar chart) and `scannet_chain.png`
  (appendix ScanNet rendered 2-hop example).
- `.nojekyll` --- forces GitHub Pages to serve files as-is (no Jekyll build).

## Local preview

```bash
cd webpage
python -m http.server 8000
# visit http://localhost:8000
```

## Deploy on GitHub Pages

1. Push the contents of `webpage/` to the root (or `docs/`) of an anonymous
   GitHub repository. Do **not** put the page in a repo whose name or owner
   leaks the authors during the review period.
2. In *Settings &rarr; Pages*, set the source to the appropriate branch and
   directory. The page will be served at
   `https://<owner>.github.io/<repo>/`.

## Anonymity

- Authors are listed as "Anonymous Author(s)" with no affiliation.
- The only outbound link is the anonymous code repo
  (`https://anonymous.4open.science/r/RelationCanon-Views-082B`).
- The footer credits the page-template lineage, not the authors.
