
# 🏠 Project 3: House Pricing Estimation

This project focuses on predicting house prices using machine learning techniques based on the Ames Housing Dataset. The goal is to develop a regression model that can accurately estimate property prices from various features of the house.

## 📊 Objective
Build a predictive model for house prices using exploratory data analysis (EDA), feature engineering, and multiple regression models.

## 📁 Dataset
- **Source:** Ames Housing Dataset
- **Target Variable:** `SalePrice`
- **Features:** Includes ~80 variables like:
  - Lot size
  - Year built
  - Number of rooms
  - Neighborhood
  - Building type
  - Garage and basement features

## 🛠️ Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost / LightGBM (optional)

## 📌 Workflow
1. **Data Cleaning** – Handling missing values, outliers, and data types.
2. **EDA** – Understanding distributions, correlations, and relationships.
3. **Feature Engineering** – Creating new features and encoding categorical variables.
4. **Modeling** – Training regression models like:
   - Linear Regression
   - Decision Tree
   - Random Forest
   - Gradient Boosting
5. **Evaluation** – Using metrics such as:
   - R² Score
   - MAE
   - RMSE
   - MAPE

## 📈 Results
- Best performing model achieved high R² and low error on test data.
- Key influential features: `OverallQual`, `GrLivArea`, `GarageCars`, `TotalBsmtSF`, `YearBuilt`.

## 📎 Outcome
A robust, generalizable regression model that estimates house prices with good accuracy—ready for use in real estate insights is XGBoost with hyperparameter tuning with estimated 90% accuracy .
