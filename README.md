# Coding Week Machine Learning Task – IIT Guwahati

This repository contains my complete submission for the Machine Learning Task
released during Coding Week by the Coding Club, IIT Guwahati.

---

## Project Objective
To predict **Crowd Energy (0–100)** for future concert venues using historical tour data,
while handling noisy data, preventing leakage, and performing proper model validation.

---

## Repository Contents

- **analysis_notebook.ipynb**  
  Complete notebook containing:
  - Data cleaning & preprocessing
  - Exploratory Data Analysis (EDA)
  - Feature engineering
  - Baseline and tuned models
  - Hyperparameter tuning using GridSearchCV

- **predictions.csv**  
  Final predictions for the test dataset (submission file).

- **findings_report.pdf**  
  Summary of data cleaning decisions, EDA insights, model choice, and results.

- **revenue_optimization.pdf**  
  Bonus analysis deriving a profit model and identifying the optimal ticket price
  for venue V_Gamma.

---

## Model Summary

- **Baseline Model:** Ridge Regression  
  - RMSE ≈ 18.13

- **Final Model:** Random Forest Regressor (tuned using 5-fold cross-validation)  
  - RMSE ≈ 16.80

The tuned model was selected due to its superior performance and ability to capture
non-linear venue-specific patterns.

---

## Bonus Task
Includes a revenue optimization analysis with:
- Explicit business assumptions
- Custom attendance and profit formulas
- Simulation-based optimization
- Profit vs ticket price visualization

---

## Author
Prachi Goel
