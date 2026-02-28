# 📊 Data Cleaning & Standardization Pipeline  
### Internship Project | Syntecxhub  

---

## 🔹 Project Overview

This repository contains a structured **data preprocessing pipeline** developed during my internship at **Syntecxhub**.

The objective was to transform raw, inconsistent data into a **clean, validated, and analysis-ready dataset** suitable for:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Workflows

This project emphasizes **reproducibility, schema consistency, and statistical validation** — core principles in production-grade data science systems.

---

## 🎯 Problem Statement

Real-world datasets often suffer from:

- Missing values  
- Duplicate records  
- Inconsistent formatting  
- Incorrect data types  
- Noisy categorical labels  
- Statistical outliers  

The goal was to design a **systematic preprocessing workflow** to address these issues while maintaining data integrity.

---

## ⚙️ Methodology

### 1️⃣ Data Inspection & Profiling

- Structural inspection using `df.info()` and `df.describe()`  
- Null-value analysis and distribution checks  
- Schema validation  

---

### 2️⃣ Missing Value Strategy

- Detection using `isnull()`  
- Mean / Median imputation for numerical variables  
- Mode imputation for categorical variables  
- Conditional row removal where appropriate  

---

### 3️⃣ Duplicate Handling

- Identification using `duplicated()`  
- Deduplication while preserving first valid occurrence  

---

### 4️⃣ Data Type Enforcement

- Explicit type casting using `astype()`  
- Datetime normalization using `pd.to_datetime()`  
- Ensured numeric precision consistency  

---

### 5️⃣ Categorical & Text Standardization

- Whitespace trimming using `.str.strip()`  
- Case normalization using `.str.lower()`  
- Label unification for categorical consistency  
- Column renaming to standardized `snake_case` schema  

---

### 6️⃣ Outlier Detection

- IQR-based anomaly detection  
- Distribution-based statistical validation  

---
## 👨‍💻 Author
**Bhaskar Mandal | Data Analyst Intern | SyntecxHub**
