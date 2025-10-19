#  Cyber-Security Project: Phishing Website Detection

This project applies **supervised machine learning** techniques to detect **phishing websites** based on URL structure, content, and pattern-based features.  
It demonstrates how data preprocessing, oversampling, and model optimization can be combined to create a reliable predictive system — crucial in cybersecurity, where missing phishing attempts is highly costly.

---

## Project Overview

The analysis focuses on:
- Detecting phishing websites using engineered URL and metadata features.  
- Handling **imbalanced data** through oversampling and class weighting.  
- Comparing multiple supervised learning models for accuracy and recall performance.  
- Optimizing model thresholds to minimize false negatives (missed phishing sites).  
- Demonstrating a machine learning workflow suited for **real-world cybersecurity applications**.

This project highlights **data-driven defense strategies**, leveraging machine learning to identify online threats proactively.

---

## Dataset

**Source:** [Phishing Website Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/simaanjali/tes-upload)

The dataset contains labeled samples of legitimate and phishing websites, with multiple engineered features extracted from:
- URL structure and domain patterns  
- Metadata and security-related attributes  

Preprocessing steps included:
- Encoding categorical URL features.  
- Handling missing values and noise.  
- Addressing class imbalance using **SMOTE** and **class weighting**.  

---

## Methodology

###  Data Preprocessing
- Cleaned and encoded categorical URL features.  
- Balanced the dataset using **SMOTE (Synthetic Minority Oversampling Technique)**.  
- Scaled numeric features to optimize model performance.  

###  Model Development
- Implemented and compared:
  - Logistic Regression  
  - Random Forest  
  - XGBoost  
- Tuned hyperparameters and adjusted decision thresholds for improved recall.  

###  Evaluation
- Evaluated models using:
  - **Precision**, **Recall**, **F1-score**, and **Confusion Matrix**.  
- Prioritized **high recall (96.6%)** to minimize false negatives — ensuring phishing attempts are rarely missed.  

---

## Tech Stack

- **Python**  
- **pandas**, **scikit-learn**, **xgboost**  
- **imbalanced-learn (SMOTE)**  
- **Matplotlib** / **Seaborn** for data visualization  
- **Jupyter Notebook** for interactive analysis  

Install dependencies:
```bash
pip install pandas scikit-learn xgboost imbalanced-learn matplotlib seaborn
