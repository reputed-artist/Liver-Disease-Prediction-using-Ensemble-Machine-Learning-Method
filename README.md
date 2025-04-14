# Liver Disease Prediction using Ensemble Machine Learning Techniques

This repository contains the source code for my **M.Tech project**, focused on improving the prediction accuracy of liver disease using **ensemble machine learning algorithms**.

## 📌 Project Overview

Liver disease is a major cause of mortality worldwide. Early diagnosis can significantly improve patient outcomes. This project aims to develop a predictive model that uses patient data to accurately detect liver disease using an **ensemble of machine learning models**.

## 🎯 Objectives

- To analyze and preprocess liver disease datasets.
- To apply various machine learning models for classification.
- To implement **ensemble techniques** to improve predictive accuracy.
- To evaluate model performance using various metrics.
- Implement code in both scaled and unscaled data to test results.

## 🛠️ Technologies Used

- **Python 3**
- **Jupyter Notebook / Google Colab**
- **Pandas, NumPy** – for data handling
- **Matplotlib, Seaborn** – for visualization
- **Scikit-learn** – for machine learning models
- **XGBoost / Random Forest / LGBM (Light Gradient Boosting Machine Classifier)** – for ensemble modeling

## 🧠 Machine Learning Techniques

The following models were used and compared:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- K-Nearest Neighbors (KNN)

### 🔁 Ensemble Models Implemented

- **Bagging** – Random Forest
- **Boosting** – XGBoost, LGBM
  

## 📊 Results [vary for scaled and unscaled data]

| Model             | Accuracy (%) |
|------------------|--------------|
| Logistic Regression | 74.3%     |
| SVM                 | 79.1%     |
| RF                  | 92.1%     |
| LGBM                | 71.1%     |
| XGBOOST             | **99.9%** |

> **Voting Classifier** with soft voting gave the best performance, showing that ensemble methods significantly improve the prediction accuracy over individual models.

## 📁 Dataset

- Dataset used: [Indian Liver Patient Dataset (ILPD)](https://www.kaggle.com/datasets/uciml/indian-liver-patient-records)
- Size: 583 records
- Features include: Age, Gender, Total Bilirubin, Alkphos Alkaline Phosphotase, etc.

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/reputed-artist/Liver-Disease-Prediction-using-Ensemble-Machine-Learning-Method.git
