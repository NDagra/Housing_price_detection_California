
# 🏠 Housing Price Prediction Project

## 📌 Overview
This project predicts housing prices in California using the California Housing dataset. It applies Linear Regression to model the relationship between housing features and median house value.

## 📂 Dataset Information
- Source: `sklearn.datasets.fetch_california_housing()`
- Features: Median income, house age, average rooms, bedrooms, population, latitude, longitude
- Target: `MedHouseVal` (Median house value)

## 🧪 Methodology
- Data Exploration using `pandas` and `seaborn`
- Feature Selection via correlation heatmap
- Linear Regression model from Scikit-learn
- Evaluation using MSE and R² score

## 📈 Key Results
- MSE: 0.5559
- R² Score: 0.5758
- Income (`MedInc`) is the strongest predictor of house value

## 📊 Visualizations
- Correlation heatmap
- Actual vs Predicted scatter plot

## 🚀 Future Improvements
- Use advanced models like Random Forest or XGBoost
- Engineer better features
- Handle capped values separately

## 📁 Deliverables
- Jupyter Notebook (`.ipynb`)
- Trained model (`.pkl`)
- This README.md
- Project report (`.docx`)
