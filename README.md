# 🏠 ML_Final_Project

### Predicting House Price in Pierce County

---

## 📌 Project Overview

This project analyzes the **Pierce County, WA 2020 house sales dataset** to identify the most influential features driving homes into higher price brackets.

Using a regression decision tree, we modeled the relationship between house features and sale price, aiming to uncover which characteristics made a home more desirable during the COVID-driven urban flight.

---

## ❓ Research Question

**Which housing features were most predictive of an increase in home sale price during 2020 in Pierce County?**

---

## 🧪 Methods

We used a `DecisionTreeRegressor` from `scikit-learn` and tuned hyperparameters using `GridSearchCV`.

Features were cleaned and one-hot encoded as needed. We removed outliers and focused on numeric and location-based predictors.

---

## 🔧 Model Details

- **Model**: `DecisionTreeRegressor`
- **Target**: `sale_price`
- **Top Features Identified**:
  - Square footage of living space
  - Number of bedrooms/bathrooms
  - Year built

---

## 🧹 Preprocessing

- Removed irrelevant columns (e.g., address, parcel number)
- Converted object and string types to categorical
- Dropped NA values
- Removed outliers using the IQR method

---

## 📈 Model Evaluation

We evaluated performance using:

- **R²**: 0.52  
- **RMSE**: 88779.23   

---

## 👥 Team

- Rebecca Vanni
- Avalon Bennett
- Thomas Cusick  

---
