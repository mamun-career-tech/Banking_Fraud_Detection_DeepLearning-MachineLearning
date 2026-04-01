# 💳 Banking Fraud Detection using Machine Learning & Deep Learning V-2

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/TensorFlow-DL-ff6f00?style=for-the-badge&logo=tensorflow" />
  <img src="https://img.shields.io/badge/Optuna-Hyperparameter%20Tuning-5c4ee5?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SHAP-Explainability-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LIME-Model%20Interpretability-success?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Dataset-Kaggle%20%7C%20ULB-red?style=for-the-badge&logo=kaggle" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />
</p>

<p align="center">
  <b>An end-to-end Banking / Credit Card Fraud Detection project built with classical Machine Learning, Deep Learning, anomaly detection, rich EDA, hyperparameter tuning, and explainable AI.</b>
</p>

## Overview

Fraud detection is one of the most impactful real-world applications of data science in the financial sector. This project focuses on detecting fraudulent credit card transactions using the **ULB / Kaggle Credit Card Fraud Detection dataset**, a highly imbalanced dataset where fraudulent transactions are extremely rare.

This repository presents a complete fraud detection pipeline including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Class imbalance handling
- Machine Learning and Deep Learning models
- Anomaly detection with Autoencoder
- Hyperparameter tuning
- Threshold analysis and calibration
- Model explainability using **SHAP** and **LIME**

---

## Dataset

**Dataset:** ULB / Kaggle Credit Card Fraud Detection Dataset

### Dataset Summary

- **Total transactions:** 284,807
- **Fraud cases:** 492
- **Normal transactions:** 284,315
- **Problem type:** Binary classification
- **Challenge:** Extreme class imbalance

This dataset is widely used for benchmarking fraud detection systems because it closely reflects the difficulty of identifying rare fraudulent activity in real financial environments.

---

## Business Problem

In real-world banking systems, fraudulent transactions make up only a tiny fraction of all activity, but they can lead to significant financial losses. Traditional models often fail in this setting because they optimize for overall accuracy rather than minority-class detection.

This project addresses that challenge by focusing on:

- Detecting rare fraud events
- Improving recall without sacrificing too much precision
- Evaluating models beyond accuracy
- Building interpretable fraud detection systems

---

## Project Objectives

- Build a robust end-to-end fraud detection pipeline
- Explore fraud patterns through detailed EDA
- Handle severe class imbalance effectively
- Compare Machine Learning and Deep Learning models
- Optimize performance using hyperparameter tuning
- Evaluate models with fraud-focused metrics
- Explain predictions using modern XAI techniques

---

## Key Features

- ✅ Comprehensive **data preprocessing**
- ✅ Rich **EDA** with distributions, correlations, PCA, and pairplots
- ✅ Multiple **imbalance handling techniques**
- ✅ **Machine Learning** and **Deep Learning** approaches
- ✅ Optional **Autoencoder anomaly detection**
- ✅ **Hyperparameter tuning** using GridSearchCV, RandomizedSearchCV, and Optuna
- ✅ Advanced evaluation with **ROC**, **PR curves**, **calibration**, and **threshold tuning**
- ✅ Model explainability using **SHAP** and **LIME**

---

## Tech Stack

### Languages & Libraries
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Plotly** *(optional for interactive visualization)*
- **Scikit-learn**
- **Imbalanced-learn**
- **TensorFlow / Keras**
- **Optuna**
- **SHAP**
- **LIME**

### Tools
- **Jupyter Notebook / Google Colab**
- **Git & GitHub**

---

## Project Workflow

```text
Dataset Loading
     ↓
Data Preprocessing
     ↓
Exploratory Data Analysis
     ↓
Class Imbalance Handling
     ↓
Model Building
  ├── Logistic Regression
  ├── MLP
  └── Autoencoder (Optional)
     ↓
Hyperparameter Tuning
     ↓
Model Evaluation
     ↓
Threshold Analysis & Calibration
     ↓
Explainability with SHAP and LIME
