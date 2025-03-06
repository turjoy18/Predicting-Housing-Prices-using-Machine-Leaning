# Predicting-Housing-Prices-using-Machine-Leaning

## Overview
This repository contains two machine learning projects that predict housing prices using different techniques:
1. **Linear Regression** applied to housing data from Dumbo, Brooklyn.
2. **XGBoost Regression** applied to housing data from Iowa.

## Datasets
- The **Dumbo, Brooklyn dataset** includes various property attributes and market factors affecting house prices in an urban setting.
- The **Iowa dataset** provides structured real estate data from a suburban/rural environment, including categorical and numerical features.

## Methodologies
### 1. Linear Regression (Dumbo, Brooklyn)
- Preprocessing: Handled missing values, normalized numerical data, and encoded categorical variables.
- Model: Implemented a simple Linear Regression model.
- Evaluation: Measured performance using RMSE and R-squared scores.

### 2. XGBoost Regression (Iowa)
- Preprocessing: Feature engineering, handling missing values, and one-hot encoding categorical variables.
- Model: Used the XGBoost algorithm with hyperparameter tuning.
- Evaluation: Assessed model accuracy using RMSE and feature importance analysis.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/turjoy18/housing-price-prediction.git
   cd housing-price-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebooks to explore the models:
   ```bash
   jupyter notebook
   ```

## Results & Findings
- The **Linear Regression model** provided a baseline prediction for housing prices in Dumbo, Brooklyn.
- The **XGBoost model** showed improved accuracy, leveraging feature selection and boosting techniques for better predictive performance.

## Future Improvements
- Incorporate additional features such as economic indicators and interest rates.
- Experiment with more advanced machine learning techniques like Neural Networks.

## Author
**turjoy18** - Passionate about Machine Learning and Data Science.

