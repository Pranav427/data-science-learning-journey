# 06_Hypothesis_Testing – Statistical Inference with Confidence Intervals & Z-Test

## 📌 Overview
This module focuses on **statistical inference** using **estimation, confidence intervals, and hypothesis testing**.  
The objective is to make **data-driven decisions** by quantifying uncertainty and testing assumptions about population parameters.

The module demonstrates how inferential statistics are applied in real-world analytical scenarios.

---

## 🛠️ Libraries Used
- `numpy`
- `scipy.stats`
- `math`

---

## 🔍 Topics Covered

### 1️⃣ Estimation & Confidence Intervals
Confidence intervals were constructed to estimate the **population mean** using:

- **t-distribution** (when population standard deviation is unknown)
- **z-distribution** (when population standard deviation is known)

A **99% confidence level** was used to reflect high statistical certainty.

#### ✔️ Results
- **99% CI (t-distribution):**  
  `[1.09, 1.387]`
- **99% CI (z-distribution, σ = 0.2):**  
  `[1.106, 1.372]`

These intervals provide a range of plausible values for the true population mean.

---

### 2️⃣ Hypothesis Testing – One-Tailed Z-Test
A **one-tailed Z-test** was performed to evaluate whether the **average weekly cost has increased**.

#### 🔹 Hypotheses
- **Null Hypothesis (H₀):** μ = 4000  
- **Alternative Hypothesis (H₁):** μ > 4000  

#### 🔹 Test Parameters
- Significance level (α): **0.05**
- Known population standard deviation
- Sample size: **25**

---

### 3️⃣ Test Statistic & Decision Rule
- **Z-statistic:** `-38.000`
- **Critical value (Zₐ):** `1.645`

Since the calculated Z-statistic does **not exceed** the critical value, the null hypothesis is **not rejected**.

#### ✔️ Conclusion
> There is **insufficient statistical evidence** to conclude that the average weekly cost has increased.

---

## ⭐ Why This Module Matters
- Introduces **inferential statistics**, a core skill in data science
- Helps quantify **uncertainty** in real-world data
- Enables **evidence-based decision making**
- Builds strong foundations for:
  - A/B testing
  - Business analytics
  - Experimental analysis
  - Machine learning evaluation

---

## 🔜 Next Module
➡️ ** Feature Engineering AND Multiple_Linear_Regression **

---

## 🚀 Skills Demonstrated
- Confidence interval estimation
- Hypothesis formulation
- Z-test implementation
- Statistical decision making
- Python-based statistical analysis

---

## ✅ Status
✔ Confidence intervals computed  
✔ Hypothesis tested and interpreted  
✔ Ready for feature engineering and modeling

