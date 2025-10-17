# Cyber-Security-Project
Overview
This project applies supervised machine learning techniques to detect phishing websites based on URL structure, content, and pattern-based features. By leveraging data preprocessing, oversampling, and model optimization techniques, it achieves strong predictive performance suitable for cybersecurity use cases where missing phishing attempts is costly.

Dataset

The dataset used in this project is publicly available on Kaggle:
Phishing Website Detection Dataset ( https://www.kaggle.com/datasets/simaanjali/tes-upload )
It contains labeled samples of legitimate and phishing websites with multiple engineered features derived from URLs and metadata. The dataset was preprocessed to handle class imbalance and optimize training efficiency.

Methodology

Data Preprocessing:
Cleaned and encoded categorical URL features.
Addressed class imbalance using SMOTE oversampling and class weighting.
Model Development:
Implemented and compared multiple supervised models (e.g., Logistic Regression, Random Forest, XGBoost).
Tuned hyperparameters and adjusted decision thresholds for optimal recall.
Evaluation:
Assessed models using metrics such as precision, recall, F1-score, and confusion matrix.
Prioritized high recall (96.6%) to minimize false negatives, ensuring phishing attempts are rarely missed.

Future Improvements

Integrate real-time URL scanning APIs for live phishing detection.
Expand dataset to include multilingual or region-specific phishing domains.
Deploy model as a web service for cybersecurity monitoring tools.

Tech Stack

Python, Pandas, Scikit-learn, XGBoost
SMOTE (Imbalanced-learn)
Jupyter Notebook
Matplotlib / Seaborn for visualization
