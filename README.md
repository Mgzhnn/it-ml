# Hands-On Machine Learning Exercises (Step by Step)

This repository documents my chapter-by-chapter practice from Aurélien Géron's book *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*.

The goal is to learn ML foundations by implementing concepts directly in notebooks, not just reading theory.

## What Is Included

- `ml_2nd_chapter.ipynb`: end-to-end ML project workflow (housing data)
- `ml_3rd_chapter.ipynb`: classification with MNIST
- `ml_4th_chapter.ipynb`: training models (linear/logistic regression)
- `ml_5th_chapter.ipynb`: decision trees
- `ml_6th_chapter.ipynb`: ensemble methods
- `ml_7th_chapter.ipynb`: dimensionality reduction (PCA)
- `ml_8th_chapter.ipynb`: clustering (K-Means and related topics)

## Tech Stack

- Python
- NumPy, Pandas, SciPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Run Locally

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Open any chapter notebook and run cells in order.

## Data and Artifacts

Large generated files and local dataset caches are intentionally excluded from git (see `.gitignore`) to keep the repository lightweight and GitHub-compatible.

If a notebook needs data, it should download it or regenerate it from code.

## Suggested Project Layout (Next Step)

```text
it-ml/
  notebooks/
  src/
  reports/
  data/            # ignored
  artifacts/       # ignored
  README.md
  requirements.txt
```

Current notebooks are kept at the repository root for continuity. As the project grows, moving them into `notebooks/` is recommended.

## Learning Notes

This is an active learning log. I improve notebooks over time by:

- adding clearer markdown explanations
- refactoring repeated code into reusable helpers
- comparing baseline vs improved model performance

## Attribution

Exercises and concepts are based on *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow* by Aurélien Géron.
