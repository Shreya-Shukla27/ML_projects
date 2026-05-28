# ML_projects

[![License](https://img.shields.io/badge/license-MIT-brightgreen)](LICENSE)
[![Notebooks](https://img.shields.io/badge/notebooks-Jupyter-orange)](#)

ML_projects — a small collection of reproducible Jupyter notebooks and helper scripts for medical binary classification experiments.

## Overview

- Notebooks and scripts for exploratory data analysis, preprocessing, model training and evaluation.
- Notable files:
  - `Copy_of_Parkinsons.ipynb` — Parkinson's disease classification experiments.
  - `Heart_disease.ipynb` — Heart disease classification experiments.
  - `compute_metrics.py` — helper to compute/save evaluation metrics.

## Quick Start

1. Create and activate a virtual environment (Windows example):

```bash
python -m venv .venv
.venv\Scripts\activate
```

Or on macOS / Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
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

## Data

- This repository includes `content/parkinsons.csv` (see `content/`). The heart disease dataset is not included by default.
- If you want to run the heart-disease notebook, place the dataset in `content/` and name it `heart.csv`, or update the notebook's data-paths accordingly.

Recommended sources:

- Parkinson's UCI: https://archive.ics.uci.edu/ml/datasets/parkinsons
- Heart Disease (Cleveland) UCI: https://archive.ics.uci.edu/ml/datasets/Heart+Disease

## Project layout

```
ML_projects/
├── Copy_of_Parkinsons.ipynb
├── Heart_disease.ipynb
├── compute_metrics.py
├── requirements.txt
└── content/ (datasets; `parkinsons.csv` included)
```

## Usage & workflow

- Open a notebook and run cells top-to-bottom. Notebooks contain explanatory cells near the top describing required files and columns.
- Use `compute_metrics.py` to load results and generate consistent metric reports when running models programmatically.

## Model performance

This section is intentionally left for you to populate with results from your experiments. To generate consistent metrics programmatically, run your training/evaluation cells in the notebooks or use the `compute_metrics.py` helper and copy the numbers here.

Example (run locally):

```bash
python compute_metrics.py --input content/parkinsons.csv --output metrics/parkinsons_metrics.json
# then open `metrics/parkinsons_metrics.json` and paste the values into this section
```

If you prefer to remove this section entirely, tell me and I will delete it.

## Contributing

- Improvements and fixes are welcome. Suggested workflow:
  1. Fork the repo
  2. Create a branch: `git checkout -b feature/your-change`
  3. Open a PR with a clear description

## License

- MIT by default. Update `LICENSE` if you require a different license.

## Contact

- Repository owner: `Shreya-Shukla27` — open an issue for questions or feature requests.

## Next steps

- If you'd like, I can run the Parkinson's notebook and populate the 'Model performance' table using the included `content/parkinsons.csv`. Tell me if you want me to run it now.
