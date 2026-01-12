# 05_EDA – Exploratory Data Analysis on Cardiotocographic Data

## 📌 Overview
This module focuses on **Exploratory Data Analysis (EDA)** using a real-world **cardiotocographic dataset**.  
The goal is to understand data structure, distributions, outliers, and relationships between features before applying any machine learning models.

EDA is a critical step in the data science pipeline as it reveals patterns, anomalies, and key insights hidden within the data.

---

## 📂 Dataset Used
- **Cardiotocographic -A5.csv**
- Observations: **2126**
- Features: **14 numerical variables**
- Domain: **Healthcare / Fetal Health Monitoring**

---

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

---

## 🔍 EDA Workflow

### 1️⃣ Data Loading & Inspection
- Loaded dataset using `pandas`
- Checked structure, data types, and memory usage using `.info()`
- Previewed records using `.head()`

---

### 2️⃣ Missing Value Handling
- Identified missing values across multiple columns
- Replaced missing values using **column-wise mean imputation**
- Ensured dataset had **no null values** after cleaning

---

### 3️⃣ Outlier Treatment
- Applied **Interquartile Range (IQR)** method
- Capped extreme values using lower and upper bounds
- Preserved data size while reducing the impact of extreme outliers

---

### 4️⃣ Statistical Summary
Computed key descriptive statistics:
- Mean
- Median
- Mode
- Standard deviation
- Quartiles (Q1, Q2, Q3)

Used:
- `.describe()`
- `.mean()`
- `.median()`
- `.mode()`

---

## 📊 Data Visualization

### 🔹 Univariate Analysis
- Histograms for all numerical features
- Boxplots to detect spread and outliers

### 🔹 Multivariate Analysis
- Correlation matrix using `.corr()`
- Heatmap visualization using **Seaborn**
- Feature-wise correlation analysis for deeper insights

---

## 🔗 Correlation & Pattern Analysis
- Identified strong and weak relationships between variables
- Analyzed correlations with key variables such as:
  - `LB` (Baseline Fetal Heart Rate)
  - `NSP` (Fetal State)
- Printed sorted correlations for **every feature** to understand interdependencies

---

## ⭐ Why This Module Matters
- Builds intuition about **healthcare datasets**
- Strengthens understanding of **statistical behavior of features**
- Helps detect **data quality issues** early
- Guides **feature selection** for machine learning
- Forms the foundation for **predictive modeling**

---

## 🔜 Next Module
➡️ **Feature Engineering & Machine Learning**  
Focus on transforming insights into features and building predictive models.

---

## 🚀 Skills Demonstrated
- Exploratory Data Analysis
- Data cleaning & preprocessing
- Outlier handling
- Statistical reasoning
- Data visualization
- Correlation analysis

---

## ✅ Status
✔ Data cleaned and analyzed  
✔ Patterns and relationships identified  
✔ Ready for modeling phase

