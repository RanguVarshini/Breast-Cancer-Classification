# Breast Cancer Classification using Machine Learning  
### Coimbra Dataset (UCI Machine Learning Repository)

## 📌 Overview
This project implements a Machine Learning–based classification system to predict the presence of **breast cancer** using **anthropometric and routine blood test parameters**.  
The aim is to assist in **early detection** using low-cost, non-invasive clinical features.

---

## 🎯 Problem Statement
Breast cancer is one of the leading causes of mortality among women worldwide. Early diagnosis significantly improves treatment outcomes.

This project formulates breast cancer detection as a **binary classification problem**, distinguishing between:
- **Healthy individuals**
- **Breast cancer patients**

using clinical and biochemical data.

---

## 📂 Dataset Information
- **Dataset Name:** Breast Cancer Coimbra Dataset  
- **Source:** UCI Machine Learning Repository  
- **Link:** http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra  

### Dataset Summary
- **Total Samples:** 116  
  - 64 Breast Cancer patients  
  - 52 Healthy controls  
- **Number of Features:** 10 (all numerical)

---

## 🔢 Predictive Features
- Age (years)  
- BMI (kg/m²)  
- Glucose (mg/dL)  
- Insulin (µU/mL)  
- HOMA  
- Leptin (ng/mL)  
- Adiponectin (µg/mL)  
- Resistin (ng/mL)  
- MCP-1 (pg/dL)

---

## 🏷️ Target Variable
- **1 → Healthy Control**
- **2 → Breast Cancer Patient**

(Binary Classification)

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook / Google Colab  

---

## 🔍 Machine Learning Workflow
1. Data loading and inspection  
2. Exploratory Data Analysis (EDA)  
3. Data preprocessing  
4. Feature scaling  
5. Model training  
6. Model evaluation  
7. Model comparison  

---

## 🧠 Models Implemented
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

## 📈 Results
The best-performing model was Logistic Regression, with sensitivity and specificity of 83%. The top predictive features were Glucose, Age, Resistin, BMI, and Insulin. These results indicate that there is some relationship between obesity/metabolic disregulation and breast cancer, and that this model may be used as a biomarker of breast cancer.
