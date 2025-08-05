# Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains a detailed Exploratory Data Analysis (EDA) on the Titanic dataset as part of **Task 2** of the AI & ML Internship program.

---

## 📌 Objective

Understand the Titanic dataset through:
- Summary statistics
- Visualizations
- Correlation analysis
- Outlier detection
- Pattern and trend recognition

---

## 🧰 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Plotly
- NumPy

---

## 📊 Steps Performed

### ✅ 1. Summary Statistics
- Used `.describe()` to view mean, median, std, etc.
- Printed dataset info using `.info()`.

### ✅ 2. Visualizations
- Created **histograms** and **boxplots** for numeric features.
- Used **countplots** for categorical variables.

### ✅ 3. Correlation & Pairplot
- Plotted **correlation matrix** using Seaborn heatmap.
- Generated **pairplot** for selected features (Age, Fare, Pclass, Survived).

### ✅ 4. Pattern & Anomaly Detection
- Identified **missing values** and visualized them using a heatmap.
- Checked **skewness** of numerical features.
- Noted trends like survival based on class, sex, and fare.

### ✅ 5. Outlier Handling
- Detected and removed outliers from the **Fare** column using the IQR method.

---

## 📌 Key Observations

- Passengers in 3rd class had the lowest survival rate.
- Female passengers were more likely to survive.
- Higher fare generally indicated a higher chance of survival.
- Data contains outliers, especially in Fare and Age.

---

## 📁 Files Included

- `Exploratory_Data_Analysis.ipynb` – Main notebook containing all code and analysis.
- `Titani-Dataset.csv` – Titanic dataset file.
- `README.md` – This documentation file.

---

## 🔗 Dataset Source

[Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---
