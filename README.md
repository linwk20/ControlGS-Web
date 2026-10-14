# ControlGS project page

Portable static research website. No build step, runtime dependencies, or external fonts.

## Local preview

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Open http://127.0.0.1:8765. The live site is https://horizon-lab.org/controlgs/, deployed through the `docs/controlgs` submodule in [the lab website repository](https://github.com/horizon-research/horizon-research.github.io). All asset links are relative.

## Content

- `index.html`: authors, method, resources, and citation
- `abstract.txt`: manuscript abstract, with LaTeX macros expanded
- `script.js`: Table 1 data, benchmark tabs, figure lightbox, and citation copy
- `assets/videos/controlgs-teaser.mp4`: browser-friendly H.264/AAC version of the supplied teaser
- `assets/images/`: figures rasterized from the manuscript and a video poster
- `assets/papers/controlgs.pdf`: main paper followed by supplementary material

Source code: [horizon-research/ControlGS](https://github.com/horizon-research/ControlGS).

Layout reference: https://jianxiapyh.github.io/Boba-project-page/. The implementation is original; research content and figures are from ControlGS. Author links follow the PowerGS project page; Junjie Zhao links to the manuscript's ORCID identifier.
