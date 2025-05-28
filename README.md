# 🏠 House Price Prediction – Advanced Regression Techniques

Predict house prices using advanced regression models on the Ames Housing dataset. This project applies thorough data cleaning, feature engineering, and multiple regression models to accurately estimate home values.

---

## 📊 Project Overview

This project tackles the Kaggle competition “House Prices: Advanced Regression Techniques” where the goal is to predict the final price of residential homes in Ames, Iowa based on 79 explanatory variables.

Key aspects of the project include:
- Data preprocessing and handling missing values
- Feature engineering and transformation
- Building and tuning models like Ridge, Lasso, and XGBoost
- Ensemble and stacking methods for improved predictions

---

## 🧱 Tech Stack

- Python 3  
- Pandas, NumPy (Data manipulation)  
- Matplotlib, Seaborn (Visualization)  
- Scikit-learn (Regression models & preprocessing)  
- XGBoost (Gradient boosting model)  
- Jupyter Notebook (Development environment)

---

## 📁 Repository Structure

house-price-predicting/
│
├── data/ # Contains train.csv, test.csv
├── notebooks/ # Jupyter notebooks for EDA and modeling
│ ├── EDA.ipynb
│ └── modeling.ipynb
├── submission/ # Sample submission files
├── README.md # Project documentation
├── requirements.txt # Required Python packages


---

## 🔍 Key Processes

### Data Cleaning & Preprocessing
- Imputation of missing values using domain knowledge and median/mode strategies  
- Removal of outliers based on feature distribution  
- Encoding categorical features with Label Encoding and One-Hot Encoding  

### Feature Engineering
- Log-transformations of skewed numerical features  
- Creation of new features like Total Square Footage  
- Scaling features with RobustScaler to reduce outlier impact  

---

## 🤖 Models Applied

| Model           | Description                      | Performance Metric (RMSE) |
|-----------------|--------------------------------|--------------------------|
| Linear Regression | Baseline                       | Higher RMSE              |
| Ridge Regression  | Regularized regression          | Improved RMSE            |
| Lasso Regression  | Feature selection + regression | Competitive RMSE         |
| XGBoost           | Gradient boosting tree model    | Best RMSE (~0.11)        |
| Stacking Ensemble | Combination of above models     | Final optimized RMSE     |

---

