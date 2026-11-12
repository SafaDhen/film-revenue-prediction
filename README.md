# Film Revenue Prediction

Regression model that predicts the revenue of a movie from its budget, genre and cast.

Kaggle challenge (regression task). Solo project.

![Predicted vs. actual revenue](docs/predicted_vs_actual.png)


## Approach

1. Clean the data and handle missing values
2. Encode genre and cast as features: [ e.g. one-hot encoding, top actors]
3. Train and compare models: [ e.g. Linear Regression, Random Forest]
4. Evaluate with [RMSE / R2 / RMSLE]



## Tech stack

Python, pandas, scikit-learn, Matplotlib, Jupyter Notebook

## Getting started

```bash
git clone https://github.com/SafaDhen/film-revenue-prediction.git
cd film-revenue-prediction
pip install -r requirements.txt
jupyter notebook
```


## What I learned

- This is a clean, minimal baseline demonstrating the correct end-to-end skeleton
 (log target → impute → fit → CV → inverse transform → submit),
 but the biggest gains would come from feature engineering and richer models

