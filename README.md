# Islamabad House Rent Price Prediction

[![Python 3.13](https://img.shields.io/badge/python-3.13-blue.svg)](https://www.python.org/downloads/release/python-3130/)
[![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange.svg)](https://jupyter.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Open Issues](https://img.shields.io/github/issues/Maaz-Saeed/islamabad-house-rent-price-prediction)](https://github.com/Maaz-Saeed/islamabad-house-rent-price-prediction/issues)
[![Last Commit](https://img.shields.io/github/last-commit/Maaz-Saeed/islamabad-house-rent-price-prediction)](https://github.com/Maaz-Saeed/islamabad-house-rent-price-prediction/commits/main)

A data science project analyzing and predicting residential rent prices in Islamabad, Pakistan.

## What's inside

`data_science_project.ipynb` covers:
- Data cleaning (missing-value imputation, rare-location filtering)
- Exploratory data analysis (price by location, price vs. area, distribution charts)
- Rent price prediction using Linear Regression and Random Forest Regressor
- Hyperparameter tuning with `RandomizedSearchCV`

## Requirements

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
```

## Data

`cleaned_house_data.csv` — the cleaned dataset produced by the notebook's data-cleaning steps (missing values imputed, rare locations removed). Later cells in the notebook (EDA, modeling) load from this file.

The notebook's earlier cells reference a raw `House_for_rent_islamabad_pk.csv`, which is not included here; those cells can be skipped by starting from the cleaned data.

## Usage

```bash
jupyter notebook data_science_project.ipynb
```
