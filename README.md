# Titanic Dataset - Data Cleaning & Preprocessing 🚢

This repository contains the data preprocessing steps performed on the Titanic Dataset as part of the AI & ML Internship Task 1.

---

## Objective
To learn and apply data cleaning and preprocessing techniques on a real-world dataset to prepare it for machine learning models.

---

## 🗃️ Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **File Used**: `Titanic-Dataset.csv.xls` (provided for the task)

---

## 🔧 Tools Used
- Python
- Pandas
- NumPy
- Seaborn / Matplotlib
- scikit-learn (for encoding and scaling)

---

## 📊 Steps Performed

### 1. **Data Exploration**
- Viewed dataset shape, data types, and head
- Checked for missing/null values

### 2. **Missing Value Handling**
- `Age`: Replaced with **median**
- `Cabin`: Replaced with **'Unknown'**
- `Embarked`: Replaced with **mode**

### 3. **Feature Dropping**
- Dropped `Ticket` and `Name` as they were not useful for modeling

### 4. **Categorical Encoding**
- Used **Label Encoding** for `Sex`, `Embarked`, and `Cabin`

### 5. **Feature Scaling**
- Applied **StandardScaler** to `Age` and `Fare` columns

### 6. **Outlier Detection**
- Visualized outliers with boxplots
- Removed extreme outliers using the **IQR method**

---

## 📁 Files Included
- `Titanic-Dataset.csv.xls` — Dataset file
- `titanic_preprocessing.ipynb` — Jupyter Notebook with complete code
- `README.md` — This file

---

## 📌 Notes
- The final dataset is now clean and ready for model training.
- You can extend this by performing feature engineering or building a model.

---

## 🔗 Submission
This work was submitted as part of the AI & ML Internship Task 1.

