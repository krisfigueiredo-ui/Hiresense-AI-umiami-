# HireSense

HireSense is a course project that ranks candidate resumes against a job description using retrieval, cosine similarity, and explainable scoring. The hosted app includes a deterministic local mode that runs without credentials; the Colab notebook contains the original OpenAI and Anthropic workflow.

**Live app:** https://krisfigueiredo-ui.github.io/Hiresense-AI-umiami-/

## Project team

- Waleed El-Jack
- Kristofor Figueiredo
- Kevin Ordet
- Jamie Shook

University of Miami, MAS 691 — Large Language Models, April 2026.

## Repository contents

| File | Purpose |
|---|---|
| `index.html` | GitHub Pages entry point |
| `app.html` | Static, responsive candidate-analysis app |
| `notebooks/hiresense_rag_demo.ipynb` | Original notebook implementation |
| `presentation/HireSense_Final_Presentation.pptx` | Final project presentation |

## Run the app

Open `index.html` directly or start a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://127.0.0.1:8000/`.

The default **Local** provider keeps resume text in the browser and requires no API key. For external LLM providers, use test credentials only or run the Colab notebook with managed secrets. Do not upload confidential resumes to a public deployment.

## Data and privacy

- The sample candidates are fictional.
- Uploaded files are processed in the browser by the static demo.
- No credentials or private resume files are included in this repository.
- Hiring decisions should include human review; model output is decision support, not a final determination.
