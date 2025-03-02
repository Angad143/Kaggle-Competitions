# **Tools and Libraries Used in Our Project**

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://img.shields.io/badge/Jupyter%20Notebook-F37626?style=flat&logo=jupyter&logoColor=white" alt="Jupyter Notebook" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" alt="Pandas" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Numpy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Scikit%20Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white" alt="Scikit Learn" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Matplotlib-003366?style=flat&logo=matplotlib&logoColor=white" alt="Matplotlib" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Seaborn-00A3E0?style=flat&logo=seaborn&logoColor=white" alt="Seaborn" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/XGBoost-3C6B3F?style=flat&logo=xgboost&logoColor=white" alt="XGBoost" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/LightGBM-9C4C32?style=flat&logo=lightgbm&logoColor=white" alt="LightGBM" style="flex: 1 1 30%;">
  <img src="https://img.shields.io/badge/Scipy-003E6C?style=flat&logo=scipy&logoColor=white" alt="SciPy" style="flex: 1 1 30%;">
</div>



# House Price Prediction: Advanced Regression Techniques

This project focuses on predicting house prices using advanced regression techniques and a stacked model approach. The dataset used comes from Kaggle's [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) competition, and the objective is to predict the final prices of homes based on a variety of features such as area, location, and overall quality.


## Project Highlights
- **Objective:** Accurately predict house prices using multiple machine learning models and ensemble techniques.
- **Techniques Used:** 
  - Feature engineering to handle missing data and categorical variables.
  - Implementation of multiple regression models including:
    - Lasso Regression
    - ElasticNet
    - Kernel Ridge Regression
    - Gradient Boosting (GBR)
    - XGBoost
    - LightGBM
  - **Stacking Models:** Combined multiple base models with a meta-model to improve overall performance.
  - **Averaging Models:** Averaged predictions from different models to achieve better predictions and reduce overfitting.

## Key Features
- **Model Selection & Evaluation:** Implemented cross-validation techniques to evaluate model performance using Root Mean Squared Logarithmic Error (RMSLE).
- **Advanced Ensemble Techniques:** Utilized stacking and averaging of models for superior predictions.
- **Feature Engineering:** Dealt with missing data, handled outliers, and transformed variables to improve model accuracy.

## Final Results
The stacked and averaged models yielded significant improvements in prediction accuracy, with the best model achieving an RMSLE score of 0.1093. This ensemble approach proved effective in combining the strengths of various regression models.

## Notebooks
- The code and model training steps are available in the Jupyter notebooks, where each step is explained in detail.

## Installation & Usage
1. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/Angad143/Kaggle-Competitions.git
   cd House-Price-Prediction
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to explore the data, train models, and evaluate results.

## Conclusion
This project demonstrates the power of ensemble techniques in improving predictive accuracy for complex regression problems. By leveraging advanced models like Gradient Boosting, XGBoost, and LightGBM, the predictions on house prices reached a highly competitive level.
