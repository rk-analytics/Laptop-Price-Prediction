# Laptop Price Prediction using Machine Learning

## Objective
Predict laptop prices using machine learning models and identify the most influential hardware and brand features affecting price.

## Dataset
- Source: Laptop specifications dataset
- Target Variable: Log-transformed laptop price
- Features include RAM, CPU, GPU, screen specs, storage, brand, and OS

## Models Implemented
- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net
- Random Forest Regressor

## Evaluation Metrics
- R² Score
- RMSE (Root Mean Squared Error)

## Key Results
| Model | Test R² | Test RMSE |
|-----|--------|-----------|
| Random Forest | 0.89 | 0.20 |
| Lasso Regression | 0.86 | 0.22 |
| Ridge Regression | 0.85 | 0.23 |
| Elastic Net | 0.79 | 0.27 |
| Linear Regression | -16.30 | 2.44 |

## Final Model
Random Forest was selected as the final model due to superior generalization and lowest prediction error.

## Key Insights
- RAM and CPU frequency are the strongest price drivers
- Screen resolution and laptop type significantly impact pricing
- Tree-based models outperform linear models for this dataset

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

## Author
Rahul
