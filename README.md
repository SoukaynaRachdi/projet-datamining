# 🩸 Blood Cell Anomaly Detection using Machine Learning

## 📌 Description

This project presents a **machine learning pipeline** for detecting blood cell anomalies using morphological characteristics extracted from blood cell images. The objective is to accurately classify blood cells as **normal** or **anomalous** by comparing the performance of several supervised machine learning algorithms.

The project includes data preprocessing, class imbalance handling using **SMOTE**, feature scaling, model training, performance evaluation, and comparison of multiple classification models.

---

## ✨ Features

* 📂 Load and preprocess a blood cell dataset.
* 🧹 Handle missing values.
* 📊 Explore class distribution.
* 📈 Visualize the dataset using **Principal Component Analysis (PCA)**.
* ⚖️ Handle class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**.
* 🔄 Standardize numerical features with **StandardScaler**.
* 🤖 Train multiple machine learning models.
* 📊 Evaluate models using several performance metrics.
* 🔍 Compare model performance and identify the best classifier.
* 📉 Visualize confusion matrices and model comparison.

---

## 🤖 Machine Learning Models

The following supervised learning algorithms are implemented and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree
* Random Forest
* Optimized Random Forest

---

## 📊 Data Analysis

The project performs several exploratory analyses, including:

* Class distribution before SMOTE.
* Class distribution after SMOTE.
* PCA visualization of blood cell samples.
* Accuracy comparison among classifiers.
* Confusion matrices for every model.
* Hyperparameter analysis:

  * K value optimization for KNN.
  * Maximum tree depth optimization for Decision Tree.

---

## 📈 Evaluation Metrics

Each model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

## 🛠 Technologies Used

### Programming Language

* Python

### Machine Learning

* Scikit-learn
* Imbalanced-learn (SMOTE)

### Data Processing

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

---



---




## 🚀 Workflow

1. Load the blood cell dataset.
2. Select relevant morphological features.
3. Split the dataset into training and testing sets.
4. Balance the training data using SMOTE.
5. Standardize the features.
6. Train different machine learning models.
7. Evaluate each classifier.
8. Compare model performances.
9. Select the best-performing model.

---

## 📊 Results

The project compares several machine learning algorithms to determine the most effective classifier for blood cell anomaly detection.

The evaluation includes:

* Model Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Classification Report
* Overall Model Comparison

The best-performing model is selected based on classification accuracy and overall predictive performance.

---

## 🎯 Project Objectives

The objective of this project is to develop a robust machine learning system capable of detecting blood cell anomalies from morphological features. By comparing multiple classification algorithms and addressing class imbalance with SMOTE, the project demonstrates an effective workflow for biomedical data analysis and medical decision support.

---

## 👩‍💻 Author

**Soukayna Rachdi**

Master BIAM (Bioinformatics & Artificial Intelligence for Precision Medicine)

FSDM Fès – Morocco
