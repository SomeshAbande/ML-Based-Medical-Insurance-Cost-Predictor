# 🏥 ML-Based Medical Insurance Cost Predictor

A machine learning–driven system that predicts **medical insurance charges** based on individual demographic and lifestyle factors such as age, BMI, smoking habits, and region. The project applies and evaluates multiple **regression models** to estimate insurance costs accurately.

---

## 📌 Project Description

The **ML-Based Medical Insurance Cost Predictor** leverages supervised machine learning techniques to analyze historical insurance data and forecast medical insurance charges. The project emphasizes **data preprocessing, feature engineering, model training, and performance evaluation** using standard regression metrics.

This project demonstrates a complete **end-to-end machine learning pipeline**, from raw data handling to model comparison and result interpretation.

---

## 🎯 Objectives

- Analyze the medical insurance dataset to identify key cost-driving factors  
- Perform data preprocessing and feature engineering  
- Train multiple regression models for insurance cost prediction  
- Evaluate and compare models using error metrics  
- Identify the best-performing model for the dataset  

---

## 🧠 Machine Learning Workflow

### 1️⃣ Data Preprocessing
- Loaded and explored the dataset using **Pandas**
- Performed statistical analysis and data inspection
- Encoded categorical features:
  - `sex`
  - `smoker`
  - `region`
- Defined:
  - **Features (X)** → age, BMI, children, smoker, region  
  - **Target (y)** → insurance charges
- Applied **feature scaling** to enhance model performance

---

### 2️⃣ Model Training
Implemented and trained the following regression models using **Scikit-learn**:
- **Linear Regression**
- **Stochastic Gradient Descent (SGD) Regressor**

All models were trained on scaled features to ensure a fair and consistent comparison.

---

### 3️⃣ Model Evaluation
- Used **Root Mean Squared Error (RMSE)** as the primary evaluation metric  
- Compared model performance based on prediction error  

---

## 📊 Results & Insights

- **SGD Regressor achieved a lower RMSE** compared to Linear Regression  
- Indicates better generalization and optimization for this dataset  
- Confirms the effectiveness of gradient-based optimization techniques for insurance cost prediction  

---

## 🛠️ Technologies & Tools Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib & Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

```bash
git clone https://github.com/AdityaNaik777/Medical_Insurance_Prediciton_Model.git
