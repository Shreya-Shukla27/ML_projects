# ML_projects

Project collection of Jupyter notebooks for binary classification experiments.

**Project Overview**

- This repository contains two analysis notebooks exploring medical classification problems (Parkinson's and heart disease). Each notebook includes exploratory data analysis, preprocessing, model training, and evaluation.

**Notebooks**

- `Copy_of_Parkinsons.ipynb` — EDA, preprocessing, feature engineering, model experiments for Parkinson's disease prediction.
- `Heart_disease.ipynb` — EDA, preprocessing, model experiments for heart disease prediction.

**Requirements**

- Python 3.8 or newer
- Common packages: numpy, pandas, scikit-learn, matplotlib, seaborn, jupyter

Install a virtual environment and required packages:

```bash
python -m venv .venv
.venv\Scripts\activate
pip install --upgrade pip
pip install -r requirements.txt
```

If you don't have `requirements.txt`, install the main packages manually:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

**Usage**

- Open the notebooks in Jupyter Notebook/Lab or VS Code and run the cells in order.
- Example:

```bash
jupyter notebook
# then open the notebook in your browser
```

**Data**

- Datasets are not included in this repository. Place datasets under a `data/` folder at the repository root with the expected filenames used in the notebooks (examples below).
- Recommended sources:
  - Parkinson's dataset (UCI): https://archive.ics.uci.edu/ml/datasets/parkinsons
  - Heart Disease (UCI — Cleveland): https://archive.ics.uci.edu/ml/datasets/Heart+Disease

Expected example filenames (update notebook cells if your filenames differ):

- `data/parkinsons.csv`
- `data/heart.csv`

Check the first cells of each notebook for the exact file path or data-loading code.

**Model Performance**

Run the notebooks to produce metrics; record results here. Use the template below to summarize your best results.

| Model               | Accuracy | Precision | Recall | F1-score | ROC AUC |
| ------------------- | -------: | --------: | -----: | -------: | ------: |
| Logistic Regression |        — |         — |      — |        — |       — |
| Random Forest       |        — |         — |      — |        — |       — |
| XGBoost / LightGBM  |        — |         — |      — |        — |       — |

Replace the placeholders above with the final numbers from your experiments.

**Notes**

- Results and reproducibility depend on the data used and package versions. Pin versions in `requirements.txt` for consistent runs.
- If you want, I can run the notebooks and fill the table (requires the datasets in `data/`).

**Author**

- Repository owner: Shreya-Shukla27
