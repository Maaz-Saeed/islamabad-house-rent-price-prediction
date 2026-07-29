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

## Usage

```bash
jupyter notebook data_science_project.ipynb
```

The notebook expects a `House_for_rent_islamabad_pk.csv` dataset in the same directory as input.
