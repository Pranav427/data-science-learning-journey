# 07_Multiple_Linear_Regression – Car Price Prediction

## 📌 Overview
This module demonstrates **Multiple Linear Regression (MLR)** to predict car prices using multiple numerical and categorical features.  
A real-world automobile dataset is used to build, evaluate, and improve regression models through **feature selection, scaling, and regularization**.

---

## 📂 Dataset Used
- **ToyotaCorolla - MLR.csv**
- Target Variable: **Price**
- Features include:
  - Age, KM driven, Fuel Type, Horse Power
  - Engine capacity, Doors, Weight, Gears, etc.

---

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

---

## 🔍 Workflow

### 1️⃣ Data Loading & Inspection
- Loaded dataset using Pandas
- Checked data types, missing values, and statistical summary
- Ensured dataset quality before modeling

---

### 2️⃣ Exploratory Analysis
- **Boxplots** to detect outliers
- **Scatter plots** to analyze relationships between predictors and price
- Correlation analysis to understand feature importance

---

### 3️⃣ Data Preprocessing
- **Label Encoding** for categorical variable (`Fuel_Type`)
- **Standardization** using `StandardScaler`
- Combined scaled features with target variable for analysis

---

### 4️⃣ Feature Selection
- Removed low-correlation features based on correlation values
- Built multiple models by progressively dropping weak predictors

---

## 📈 Model Building & Evaluation

### 🔹 Model 1
- Removed `Cylinders` due to weak correlation  
- **RMSE:** 1359.147  
- **R² Score:** 0.845  

### 🔹 Model 2 (Best Model)
- Removed low-impact features (`Cylinders`, `Fuel_Type`, `Automatic`, `Gears`)  
- **RMSE:** 1337.144  
- **R² Score:** 0.850  

### 🔹 Model 3
- Further feature reduction  
- **RMSE:** 1352.954  
- **R² Score:** 0.846  

📌 **Model 2 performed best** with the lowest RMSE and highest R² score.

---

## 🔧 Regularization Techniques

### ✔️ Lasso Regression (L1)
- Helps with feature selection
- Shrinks less important coefficients to zero

### ✔️ Ridge Regression (L2)
- Reduces multicollinearity
- Controls large coefficient values

Lasso and Ridge models were applied to **all three MLR models** for comparison.

---

## 📘 Conceptual Understanding

### 🔹 Normalization vs Standardization
- **Normalization:** Scales data between 0 and 1
- **Standardization:** Converts data to mean = 0 and std = 1
- Standardization is preferred for regression models

---

### 🔹 Handling Multicollinearity
- Drop highly correlated features
- Use **Variance Inflation Factor (VIF)**
- Apply **Ridge or Lasso Regression**

---

## ⭐ Why This Module Matters
- Builds strong foundations in **predictive modeling**
- Demonstrates real-world **feature selection**
- Teaches **model evaluation & comparison**
- Introduces **regularization techniques**
- Essential for regression-based ML problems

---

## 🔜 Next Module
➡️ **Logistic Regression**

---

## 🚀 Skills Demonstrated
- Multiple Linear Regression
- Feature encoding & scaling
- Correlation-based feature selection
- Model evaluation (RMSE, R²)
- Lasso & Ridge regularization
- Practical ML workflow

---

## ✅ Status
✔ Regression models built  
✔ Best model selected  
✔ Regularization applied  
✔ Ready for classification models

