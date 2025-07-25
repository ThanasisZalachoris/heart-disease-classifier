# Heart Disease Classification

This project presents a complete machine learning workflow to classify the presence of heart disease in patients based on various health metrics. It is built in Python using standard data science libraries and demonstrates data preprocessing, feature engineering, model selection, and performance evaluation.

## 🔍 Problem Statement

Given a set of medical attributes (e.g., age, sex, cholesterol, resting blood pressure, etc.), the goal is to predict whether a patient has heart disease. This is a **binary classification problem** based on the [Cleveland Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease).

## 📊 Dataset Features

- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Resting ECG
- Maximum heart rate
- Exercise-induced angina
- ST depression
- Slope of ST segment
- Number of major vessels
- Thalassemia
- Target (0 = No disease, 1 = Disease)

## 🧠 Methodology

- 🔍 **Exploratory Data Analysis (EDA)**
- ⚙️ **Data Preprocessing**
- 🔢 **Feature Selection**
- 📈 **Model Training**: Logistic Regression, Random Forest, XGBoost
- 🧪 **Evaluation**: Accuracy, Precision, Recall, F1-score, Confusion Matrix
- 📊 **Visualization**: Seaborn, Matplotlib for EDA and model results

## 📦 Requirements

All required libraries are listed in `requirements.txt`. To install:

```bash
pip install -r requirements.txt
jupyter lab

Model Performance
Best-performing model: Random Forest Classifier

Accuracy: ~0.85

F1-score: ~0.83

AUC: ~0.87

🧠 Author
Athanassios Zalachoris
Tourism & Data Intelligence | ML Developer | BI Analyst
