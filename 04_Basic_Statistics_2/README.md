#📘 Basic_Statistics_2 – Healthcare Data Processing with Pandas

## 📌 Overview
This module focuses on real-world data handling using **Pandas** by working with healthcare-related datasets.  
It demonstrates how to load, clean, transform, merge, and restructure patient and billing data efficiently.

The workflow simulates a practical data preprocessing pipeline commonly used in data analytics and data science projects.

---

## 📂 Datasets Used
- **patient_Data.csv** – Contains patient demographic and visit details  
- **billing_Data.csv** – Contains billing and payment-related information  

---

## 🛠️ Libraries Used
- `numpy`
- `pandas`

---

## 🔍 Key Operations Performed

### 1️⃣ Load Datasets & Inspect Structure
- Loaded patient and billing datasets
- Inspected data types, non-null counts, and memory usage using `.info()`
- Previewed records using `.head()`

---

### 2️⃣ Column Selection
- Selected only billing-relevant columns:
  - `PatientID`
  - `Department`
  - `Doctor`
  - `BillAmount`

---

### 3️⃣ Data Cleaning
- Removed administrative columns such as:
  - `ReceptionistID`
  - `CheckInTime`
- Eliminated duplicate patient records using `PatientID`

---

### 4️⃣ Handling Missing Values
- Filled missing values in `BillAmount` using the column mean to maintain data consistency

---

### 5️⃣ Dataset Integration
- Merged patient and billing datasets using `PatientID`
- Ensured relational integrity between patient and billing information

---

### 6️⃣ Data Expansion
- Added new patient records using **row-wise concatenation**
- Appended insurance and final billing details using **column-wise concatenation**

---

### 7️⃣ Final Dataset Creation
- Constructed a clean and structured final dataset including:
  - Patient details
  - Billing amount
  - Insurance coverage
  - Final payable amount

---

## 📊 Final Dataset Columns
- `PatientID`
- `Department`
- `Doctor`
- `BillAmount`
- `InsuranceCovered`
- `FinalAmount`

---

## ⭐ Why This Module Matters
- Demonstrates **end-to-end data preprocessing**, a critical step in any data science project
- Builds strong foundations in **Pandas operations** used in industry
- Mirrors **real healthcare data workflows** involving multiple datasets
- Prepares data for advanced analysis and visualization stages

---

## 🔜 Next Module
➡️ **EDA (Exploratory Data Analysis)**  
Focus on understanding data patterns, distributions, outliers, and relationships using statistical summaries and visualizations.

---

## 🚀 Tools & Skills Demonstrated
- Data preprocessing
- Data wrangling
- Dataset merging & transformation
- Python (Pandas & NumPy)

---

## ✅ Status
✔ Completed and validated dataset pipeline  
✔ Ready for EDA and advanced analytics

