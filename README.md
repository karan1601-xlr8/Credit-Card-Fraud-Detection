# Credit_Card_fraud_detection By Karan Raj
This project aims to build a machine learning model to detect fraudulent credit card transactions. The dataset is highly imbalanced, with fraudulent transactions accounting for only 0.172% of the total. The main challenge is handling this imbalance while ensuring the model effectively identifies fraud without generating excessive false positives.

🚀 Project Overview

Goal: Detect fraudulent transactions from anonymized credit card data.

Techniques Used:

Data preprocessing & feature scaling

Handling class imbalance using SMOTE/undersampling/oversampling

Machine Learning models: Logistic Regression, Random Forest, XGBoost, etc.

Evaluation metrics: Precision, Recall, F1-score, ROC-AUC

Tools: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn



📊 Results

Models tested: Logistic Regression, Random Forest, XGBoost, Neural Network

Metrics used: ROC-AUC, Precision, Recall, F1-Score, Confusion Matrix

Best performing model achieved:

Recall (Fraud detection): ~95%

ROC-AUC: ~99%

📌 Future Work

Implement deep learning models (LSTMs/Autoencoders).

Deploy the model using Flask/Streamlit for real-time fraud detection.

Explore anomaly detection techniques.
