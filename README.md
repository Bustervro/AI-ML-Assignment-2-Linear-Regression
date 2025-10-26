# AI-ML-Assignment-2-Linear-Regression
**Author:** ADEN OSMAN (replace with your name if different)

## Dataset used
- Diabetes (sklearn.load_diabetes) - used as fallback
- Number of rows: 442, number of columns: 11
- Target variable: **target**

## Selected feature and engineered feature
- Selected numerical feature: **age**
- Engineered feature created: **age_squared**

## Data cleaning steps
- Imputed missing values with column medians for selected features and target (if any).
- Removed obvious outliers in selected features (points beyond 3 standard deviations).

## Model
- Algorithm: Linear Regression (scikit-learn)
- Features used: **age**, **age_squared**
- Train/test split: 80/20

## Evaluation metrics (on test set)
- Mean Squared Error (MSE): 5649.6516
- R-squared (R2): 0.0344

## Files included
- `AI-ML-Assignment-2-Linear-Regression.ipynb` : Jupyter Notebook with analysis and code.
- `regression_scatter_line.png` : Scatter plot with regression line.
- `README.md` : This file.

## Notes
- The regression line on the scatterplot is produced by holding **age_squared** at its median value and plotting model predictions across a range of **age** values. This visualizes the relationship between the primary feature and the target while controlling for the engineered feature.
