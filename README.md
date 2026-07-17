# Diabetes Disease Progression Prediction with Gradient Boosting

A machine learning project that predicts diabetes disease progression using **Gradient Boosting Regression** on the Scikit-learn Diabetes dataset. The notebook demonstrates an end-to-end regression workflow including data exploration, feature selection, preprocessing, hyperparameter optimization, and model evaluation.

## Features

- Exploratory Data Analysis (EDA)
- Correlation heatmap visualization
- Feature selection using correlation scores
- Train/test split
- Feature scaling with StandardScaler
- Gradient Boosting Regressor
- Hyperparameter optimization using RandomizedSearchCV
- Performance evaluation using R² score

## Dataset

This project uses the built-in **Scikit-learn Diabetes Dataset**, containing clinical measurements from diabetes patients with the target variable representing disease progression one year after baseline.

Features include:

- Age
- Sex
- BMI
- Blood Pressure
- S1–S6 blood serum measurements

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## Workflow

1. Load the diabetes dataset
2. Perform exploratory data analysis
3. Visualize feature correlations
4. Select relevant features
5. Split data into training and testing sets
6. Scale the data
7. Train a Gradient Boosting Regressor
8. Optimize hyperparameters with Randomized Search
9. Evaluate model performance using R²

## Model

The project uses:

- **GradientBoostingRegressor**
- **RandomizedSearchCV** for hyperparameter tuning

Optimized parameters include:

- Number of estimators
- Learning rate
- Maximum tree depth
- Subsample ratio
- Minimum samples per leaf

## Results

The notebook reports:

- Best cross-validation R² score
- Optimal hyperparameters
- Final test R² score

## Future Improvements

- Compare against XGBoost, LightGBM, and CatBoost
- Feature importance analysis
- SHAP explainability
- Cross-validation benchmarking
- Model deployment with a web interface

## Repository Structure

```
.
├── diabetes_Boosting.ipynb
└── README.md
```
