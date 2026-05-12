# 🩺 Diabetes Risk Predictor — Machine Learning Analysis System

<p align="center">

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-darkgreen?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-teal?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-High-success?style=for-the-badge)

</p>

> Diabetes Risk Predictor is a machine learning project that predicts whether a patient is diabetic or non-diabetic using medical diagnostic data from the Pima Indians Diabetes Dataset.  
> Built using Python, Scikit-learn, Pandas, and data visualization libraries with a complete ML workflow including preprocessing, feature engineering, model training, and evaluation.

---

# 📌 Project Overview

This project focuses on predicting diabetes risk using multiple machine learning classification models.

The workflow includes:

- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Missing Value Handling
- Feature Engineering
- Model Building
- Performance Evaluation
- Prediction on New Patient Data

---

# 📂 Dataset Information

Dataset Used:
- **Pima Indians Diabetes Dataset**

Features include:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

Target Variable:
- `Outcome`
  - `1` → Diabetic
  - `0` → Non-Diabetic

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🧹 Data Preprocessing

Implemented preprocessing techniques such as:

- Replacing invalid zero values
- Handling missing values using imputation
- Feature scaling
- Feature engineering
- One-hot encoding categorical features

---

# 🤖 Machine Learning Models

The following models were trained and compared:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

Evaluation metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

---

# 📈 Data Visualization

Visualizations created include:

- Correlation Heatmaps
- Distribution Plots
- Count Plots
- ROC Curves
- Confusion Matrices

---

# 🚀 How to Run

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/mohammedasad2518/diabetes-risk-predictor.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd diabetes-risk-predictor
```

---

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📁 Project Structure

```text
diabetes-risk-predictor/
│
├── 01_eda.ipynb
├── 02_data_cleaning.ipynb
├── 03_model_building.ipynb
├── diabetes_cleaned.csv
├── utils.py
├── README.md
└── requirements.txt
```

---

# 🎯 Future Improvements

- Hyperparameter tuning
- Model deployment using Flask/Streamlit
- Deep learning implementation
- Real-time prediction system

---
