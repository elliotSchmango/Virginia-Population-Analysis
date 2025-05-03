# Virginia Population Modeling by Elliot Hong & Thomas Welch

This project uses machine learning to predict annual population estimates across Virginia using demographic data.

## Models
- Linear Regression (baseline)
- Random Forest Regressor
- LSTM Neural Network

## Methods
- One-hot encoding, scaling, feature selection
- 5-fold CV with RMSE and R² evaluation

## Key Results
- Random Forest had best performance (RMSE ≈ 266)
- LSTM struggled due to limited temporal data
- Top features: age, year, locality, race

## Data
[Virginia Single-Race Population Estimates](https://data.virginia.gov/dataset/vdh-virginia-single-race-population-estimates)

## Files
- `VA_Population_Modeling.ipynb`: modeling notebook
- `template.tex`: final report (LaTeX)
- `figures/`: plots
