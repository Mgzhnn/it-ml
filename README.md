# Hands-On Machine Learning Workflows

Applied machine learning notebooks built while working through core ML topics: regression, classification, training algorithms, trees, ensembles, dimensionality reduction, clustering, Gaussian mixtures, and anomaly detection.

The notebooks are written as workflow-style ML case studies rather than Q&A notes. Each notebook frames the objective, data, metric, validation approach, modeling stages, and next steps. Datasets are downloaded locally when needed and are intentionally not committed.

## Notebooks

| Notebook | Focus |
|---|---|
| `01_tabular_regression_workflow.ipynb` | California housing regression, preprocessing pipelines, SVR tuning, feature selection, custom transformers, bike sharing regression |
| `02_classification_workflow.ipynb` | MNIST KNN, image augmentation, Titanic survival prediction, spam classification |
| `03_softmax_regression_from_scratch_workflow.ipynb` | Softmax regression from scratch with NumPy, batch gradient descent, regularization, early stopping |
| `04_decision_tree_workflow.ipynb` | Decision tree tuning on moons and a manual random-forest-style majority vote ensemble |
| `05_ensemble_learning_workflow.ipynb` | Voting and stacking ensembles on MNIST |
| `06_dimensionality_reduction_workflow.ipynb` | PCA speed/accuracy experiments and MNIST visualization with t-SNE, PCA, LLE, and MDS |
| `07_unsupervised_learning_workflow.ipynb` | Olivetti faces clustering, K-Means distance features, Gaussian mixtures, anomaly detection |

## Setup

Create an environment and install dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebooks with Jupyter or VS Code.

Some notebooks use smaller default subsets so they run quickly. Search for flags such as `RUN_EXPENSIVE_MNIST` if you want to run the full experiments.

## Repository Hygiene

The repository excludes:

- downloaded datasets and local dataset caches
- generated model files
- memory-mapped arrays
- temporary PDF/image render folders
- the source book PDF
- Jupyter checkpoints and editor metadata

This keeps the GitHub repository focused on the workflow notebooks and reproducible code.
