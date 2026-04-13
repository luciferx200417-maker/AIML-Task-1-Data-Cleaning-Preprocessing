# AIML-Task-1-Data-Cleaning-Preprocessing

# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

## 📌 Project Overview
This project is part of an AI & ML Internship task. The goal is to clean and preprocess raw data to make it suitable for machine learning models.

We use the Titanic dataset to perform data cleaning, handle missing values, encode categorical variables, scale features, and remove outliers.

---

## 🎯 Objective
- Learn how to clean raw datasets
- Handle missing values effectively
- Convert categorical data into numerical format
- Normalize/standardize features
- Detect and remove outliers

---

## 🛠 Tools & Technologies
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset
Dataset used: Titanic Dataset  

You can download it from:
https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

---

## ⚙️ Steps Performed

### 1. Data Exploration
- Viewed dataset using `.head()`
- Checked data types and structure
- Identified missing values

### 2. Handling Missing Values
- Filled `Age` with median
- Filled `Embarked` with mode
- Dropped `Cabin` column

### 3. Encoding Categorical Variables
- Converted `Sex` into numerical (0,1)
- Applied One-Hot Encoding on `Embarked`

### 4. Feature Scaling
- Applied Standardization using `StandardScaler`

### 5. Outlier Detection & Removal
- Visualized using boxplots
- Removed outliers using IQR method

### 6. Final Dataset
- Cleaned dataset saved as `cleaned_titanic.csv`

---

## 📊 Results
- Removed missing values successfully
- Converted categorical data into usable format
- Reduced noise by removing outliers
- Dataset is now ready for machine learning models

---

## 📁 Project Structure
