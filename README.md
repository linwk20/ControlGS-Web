# ControlGS project page

Portable static research website. No build step, runtime dependencies, or external fonts.

## Local preview

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765. Deployment is intentionally not configured; all asset links are relative, so the site can be served from a domain root or project subdirectory.

## Content

- `index.html`: authors, method, resources, and citation
- `abstract.txt`: manuscript abstract, with LaTeX macros expanded
- `script.js`: Table 1 data, benchmark tabs, figure lightbox, and citation copy
- `assets/videos/controlgs-teaser.mp4`: browser-friendly H.264/AAC version of the supplied teaser
- `assets/images/`: figures rasterized from the manuscript and a video poster
- `assets/papers/controlgs.pdf`: main paper followed by supplementary material

The original video is preserved outside this repository in Downloads. No arXiv identifier or source-code repository has been invented: add their links once confirmed. Before publishing, confirm the paper version and final citation, and set a canonical URL/social image URL for the chosen host. Individual repository files should be checked against that host's size limits.

Layout reference: https://jianxiapyh.github.io/Boba-project-page/. The implementation is original; research content and figures are from ControlGS. Author links use the manuscript's ORCID identifiers.
