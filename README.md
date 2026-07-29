# Islamabad House Rent Price Prediction

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
