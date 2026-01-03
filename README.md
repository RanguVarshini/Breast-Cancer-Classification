# Breast Cancer Classification – Coimbra Dataset (Machine Learning)

This project implements a **Machine Learning–based classification system** to predict the presence of **breast cancer** using the **Breast Cancer Coimbra Dataset** from the UCI Machine Learning Repository.

The dataset consists of **anthropometric measurements and routine blood test parameters**, making it suitable for developing low-cost and non-invasive diagnostic support tools.

---

## 📌 Project Description

Breast cancer is one of the leading causes of cancer-related mortality among women.  
Early detection using accessible biomarkers can significantly improve treatment outcomes.

This project builds predictive models to classify individuals as:
- **Healthy Control**
- **Breast Cancer Patient**

using physiological and biochemical features collected from routine clinical tests.

---

## 📂 Dataset Information

- **Dataset Name:** Breast Cancer Coimbra Dataset  
- **Source:** UCI Machine Learning Repository  
- **Dataset Link:**  
  http://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Coimbra  

- **Total Samples:** 116  
  - 64 Breast Cancer patients  
  - 52 Healthy controls  

- **Number of Features:** 10 (all quantitative)

---

## 🔢 Predictive Features

| Feature Name | Description | Unit |
|-------------|------------|------|
| Age | Age of the subject | years |
| BMI | Body Mass Index | kg/m² |
| Glucose | Plasma glucose concentration | mg/dL |
| Insulin | Serum insulin | µU/mL |
| HOMA | Homeostasis Model Assessment | – |
| Leptin | Serum leptin | ng/mL |
| Adiponectin | Serum adiponectin | µg/mL |
| Resistin | Serum resistin | ng/mL |
| MCP-1 | Monocyte Chemoattractant Protein-1 | pg/dL |

---

## 🎯 Classification Labels

- **1 → Healthy Control**
- **2 → Cancer Patient**

(Binary Classification Problem)

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Machine Learning Workflow

1. Data loading and inspection  
2. Data preprocessing and normalization  
3. Exploratory Data Analysis (EDA)  
4. Feature scaling  
5. Model training  
6. Performance evaluation  
7. Result comparison  

---

## 🏗️ Models Implemented

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
