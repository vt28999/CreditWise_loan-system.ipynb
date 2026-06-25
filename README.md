# 📊 Credit Wise - Loan Approval Prediction

A machine learning project that predicts whether a loan application will be approved based on applicant demographics, financial information, employment details, and credit history.

## 🚀 Overview

Credit Wise is an end-to-end loan approval prediction pipeline that performs:

- Data Cleaning & Preprocessing
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Feature Scaling
- Feature Engineering
- Model Training & Evaluation
- Model Comparison and Selection

The project helps financial institutions automate loan approval decisions using data-driven insights.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 📂 Workflow

### 1️⃣ Data Preprocessing
- Missing value imputation using `SimpleImputer`
- Numerical features filled using mean values
- Categorical features filled using most frequent values

### 2️⃣ Exploratory Data Analysis
- Class distribution analysis
- Income distribution analysis
- Credit score analysis
- Outlier detection using boxplots
- Correlation analysis using heatmaps

### 3️⃣ Feature Engineering
- Polynomial feature generation
- Credit Score transformations
- Debt-to-Income ratio enhancements

### 4️⃣ Feature Encoding
- Label Encoding
- One Hot Encoding

### 5️⃣ Feature Scaling
- Standardization using `StandardScaler`

### 6️⃣ Model Training
The following machine learning models were evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

---

## 🏆 Best Performing Model

**Gaussian Naive Bayes** achieved the best precision score among all evaluated models.

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📁 Dataset Features

Some important features used in prediction:

- Applicant Income
- Coapplicant Income
- Credit Score
- Loan Amount
- Debt-to-Income Ratio
- Employment Status
- Marital Status
- Education Level
- Property Area
- Loan Purpose

---

## 🔥 Project Highlights

✔ Complete ML Pipeline  
✔ Real-world Financial Dataset  
✔ Feature Engineering Techniques  
✔ Multiple Model Comparison  
✔ Production-ready Workflow  

---

## 📷 Sample Pipeline

```text
Raw Data
   ↓
Data Cleaning
   ↓
EDA
   ↓
Encoding
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Evaluation
   ↓
Loan Approval Prediction
