# 🏡 House Price Predictor

This project uses the **Boston Housing Dataset** to predict median house prices using the **Linear Regression**. It demonstrates the complete machine learning workflow — from data exploration to model training, evaluation, and saving for the future use.

---

## 📊 Dataset Overview

The dataset contains information about housing in Boston suburbs, with 13 input features such as:
- 🏙️ CRIM: Crime rate
- 🏠 RM: Average number of rooms
- 🌊 CHAS: Proximity to Charles River
- 📚 PTRATIO: Student–teacher ratio
- 📈 LSTAT: % of lower status population  
...and more.

The target variable is:
- **MEDV**: Median house value in $1000s.

---

## 🔍 Features of This Project

✅ Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
✅ Linear Regression using Scikit-learn  
✅ Model evaluation with MAE, RMSE, and R²  
✅ Scatter plot of Actual vs Predicted prices  
✅ Model saved using Joblib for reuse  
✅ Clean, modular code in Jupyter Notebook

---

## 🧠 ML Concepts Used

- Supervised Learning (Regression)
- Train-Test Split
- Correlation Analysis
- Evaluation Metrics

---

## 📦 Installation

Clone the repo and install dependencies:
```bash
git clone https://github.com/yourusername/house-price-predictor.git
cd house-price-predictor
pip install -r requirements.txt
