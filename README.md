# Machine-Learning Coursework — COMP 442

A historical collection of notebook-based ML assignments, including housing/tabular-data exploration and classification exercises associated with MNIST/SVM coursework.

## Repository map

| Folder | Material |
|---|---|
| [Project1/](Project1/) | Housing/tabular notebooks, a small Iris input and assignment report |
| [Project3/](Project3/) | Classification notebooks and assignment report |
| [Project1/Housing.ipynb](Project1/Housing.ipynb) | Housing workflow |
| [Project3/MNIST_Classifier.ipynb](Project3/MNIST_Classifier.ipynb) | Classification/metric exploration |
| [Project3/Project3.ipynb](Project3/Project3.ipynb) | Additional project notebook |

[Employer guide](docs/EMPLOYER_GUIDE.md)

## How to review or reproduce

Clone the repository and open a notebook in Jupyter. Inspect its imports, data-loading cells, paths and split logic before running all cells. There is no consolidated dependency lockfile or verified one-command setup. Some cells can download datasets, for example via scikit-learn's OpenML interface.

Stored notebook output is a historical artifact, not a fresh execution result. This documentation update did not rerun training or assert a test-set accuracy.

## What this demonstrates

Exploratory analysis, feature/model experimentation, notebook workflows and classification evaluation. Compare the chosen metric with class balance and split design; accuracy alone is not an adequate assessment in every problem.

## Coursework and limitations

Assignment PDFs and original specifications retain their attribution. Use these implementations for study and review; do not submit them as your own coursework. Historical IDE metadata remains in the repository but is not part of the recommended reading path.

This is an educational archive, not a deployed ML service or a production-ready benchmark.
