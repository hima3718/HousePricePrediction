# House Price Prediction

## Project Overview
Built regression models to predict residential house prices based on
features like area, bathrooms, air conditioning, parking, and stories.

## Dataset
- 545 records, 13 features
- Source: Kaggle — Housing Prices Dataset

## Tasks Completed
-  Task 1 — Data Loading & Exploration
-  Task 2 — Data Cleaning & Encoding
-  Task 3 — Linear Regression + Random Forest models
-  Task 4 — Visualizations (4 charts)
-  Task 5 — Insights & Summary

## Model Results
| Model | MAE | RMSE | R² |
|---|---|---|---|
| Linear Regression | ₹9,70,043 | ₹13,24,507 | 0.6529 |
| Random Forest | ₹10,14,947 | ₹13,99,769 | 0.6124 |

 **Winner: Linear Regression** (higher R²)

## Key Findings
- **Area** is the #1 price driver (46.8% importance)
- **Bathrooms** rank 2nd (15.3%)
- Top 5 features explain 80%+ of price variation
- Bedrooms matter less than bathrooms

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Google Colab

## Files
| File | Description |
|---|---|
| `analysis.ipynb` | Main Jupyter Notebook (all 5 tasks) |
| `Housing.csv` | Dataset |
| `summary.pdf` | 1-page findings report |
| `Charts/` | All visualizations |
