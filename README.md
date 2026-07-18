# HireSense AI

An AI-assisted hiring/screening concept built for a University of Miami course project.

**Live demo:** https://krisfigueiredo-ui.github.io/Hiresense-AI-umiami-/

## What's in this repo

| File | What it is |
|---|---|
| `index.html` / `HireSense_InClass_Demo.html` | The interactive in-class demo (fully self-contained — no external dependencies) |
| `HireSense_Colab (2).ipynb` | The Colab notebook behind the project |
| `HireSense_AI_Final (1).pptx` | Final presentation deck |

## Running the demo locally

No build step — open `index.html` in any browser, or serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000/
```

Every push to `main` republishes the demo to GitHub Pages automatically via
`.github/workflows/pages.yml` (only the demo page is published — the notebook and deck stay
repo-only).
