# ML_projects

Project collection of Jupyter notebooks for binary classification experiments.

**Project Overview**

- This repository contains two analysis notebooks exploring medical classification problems (Parkinson's and heart disease). Each notebook includes exploratory data analysis, preprocessing, model training, and evaluation.
# ML_projects

[![License](https://img.shields.io/badge/license-MIT-brightgreen)](LICENSE)
[![Notebooks](https://img.shields.io/badge/notebooks-Jupyter-orange)](#)

ML_projects — a small collection of reproducible Jupyter notebooks for medical binary classification experiments.

Overview
--------

- Two focused notebooks for exploratory data analysis, feature engineering, model training and evaluation:
  - `Copy_of_Parkinsons.ipynb` — Parkinson's disease classification experiments.
  - `Heart_disease.ipynb` — Heart disease classification experiments.

Why this repo
--------------

- Clean, self-contained notebooks that demonstrate common ML workflows: data cleaning, visualization, feature selection, model comparison, and simple deployment-ready exports (models/metrics).

Quick Start
-----------

1. Create and activate a virtual environment:

```bash
python -m venv .venv
.venv\Scripts\activate
```

2. Install dependencies:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

3. Start Jupyter and open the notebooks:

```bash
jupyter notebook
```

Data
----

- Datasets are not included. Create a `data/` folder at the repository root and place the files used by the notebooks. Example filenames expected by the notebooks:
  - `data/parkinsons.csv`
  - `data/heart.csv`

Recommended sources:

- Parkinson's UCI: https://archive.ics.uci.edu/ml/datasets/parkinsons
- Heart Disease (Cleveland) UCI: https://archive.ics.uci.edu/ml/datasets/Heart+Disease

Project layout
--------------

```
ML_projects/
├── Copy_of_Parkinsons.ipynb
├── Heart_disease.ipynb
├── requirements.txt
└── data/ (place datasets here)
```

Usage & workflow
----------------

- Open a notebook, run cells top-to-bottom. Each notebook contains a 'Notes' and 'Data' cell at the top explaining required files and columns.
- Use the provided evaluation cells to compare models and record final metrics in the 'Model Performance' section below.

Model performance (template)
----------------------------

Fill this table with your best experiment results after running the notebooks:

| Model | Accuracy | Precision | Recall | F1-score | ROC AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | — | — | — | — | — |
| Random Forest | — | — | — | — | — |
| XGBoost / LightGBM | — | — | — | — | — |

Contributing
------------

- Improvements and fixes are welcome. Suggested workflow:
  1. Fork the repo
  2. Create a branch: `git checkout -b feature/your-change`
  3. Open a PR with a clear description

License
-------

- MIT by default. Update `LICENSE` if you require a different license.

Contact
-------

- Repository owner: `Shreya-Shukla27` — open an issue for questions or feature requests.

Notes
-----

- If you want, I can run the notebooks and populate the 'Model performance' table — add datasets to `data/` and tell me to run them.
