This repository contains a single notebook that explores campus placement data and builds a baseline classifier to predict whether a student is placed.

## Notebook

- `sl_i_coding_assignment.ipynb`

## What the notebook covers

- Data loading and quick inspection
- Exploratory data analysis (categorical plots, correlations)
- Basic preprocessing (dropping unused columns, one-hot encoding)
- Train/dev/test split
- Logistic regression baseline
- Model evaluation: confusion matrix, accuracy, precision, recall, ROC/AUC, precision-recall curve
- Simple overfitting check and outlier visualization

## Dataset

The dataset is downloaded in the notebook from:

- https://raw.githubusercontent.com/amm-ik/ml-datasets/main/module-1/placementData.csv

## Requirements

- Python 3.8+
- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn
- statsmodels

Install dependencies:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn statsmodels
```

## How to run

Open the notebook and run the cells in order.
