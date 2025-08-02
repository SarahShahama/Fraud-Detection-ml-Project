# 🛡️ Fraud Detection in Financial Transactions

## 📄 Project Overview
This project aims to build a robust machine learning model to detect fraudulent financial transactions using the **Online Payment Fraud Detection Dataset**. The key challenge is to accurately identify fraudulent activity while minimizing false positives.

## 🎯 Objectives
- Handle class imbalance and improve model precision.
- Evaluate multiple classification models (Logistic Regression, Random Forest, XGBoost, SVM).
- Select the best-performing model based on validation and test performance metrics.

## 🧠 Models Used
- Logistic Regression  
- Random Forest  
- XGBoost  
- Support Vector Machine (SVM)  

## 🧪 Dataset
- **Source**: [Online Payment Fraud Detection Dataset (Kaggle)](https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset)
- **Rows Used**: Sampled 300,000 rows from the full dataset for efficient processing in Google Colab.
- **Resampling**: SMOTENC used to address class imbalance.

## 📊 Results Summary
- Best-performing model: `Random Forest'.
- Achieved high ROC AUC, precision, and recall.
- Class imbalance handled effectively.
project/
│
├── Project 2 final code.ipynb # Main Jupyter notebook
├──https://www.kaggle.com/datasets/rupakroy/online-payments-fraud-detection-dataset #dataset
├── LICENSE # License file
├── README.md # This file
└── project 2 report final_compressed.pdf  # Final report 

bash
Copy
Edit

## 🔧 How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
Install dependencies
(e.g., run inside Colab or locally using pip install -r requirements.txt)

Open and run fraud_detection.ipynb

✅ Requirements
Python 3.8+

pandas, numpy

matplotlib, seaborn

scikit-learn

xgboost

imbalanced-learn

🙏 Acknowledgment
This project was developed as part of an internship at Gen Z Hgateway.

⚠️ License
This project is not open-source. All rights reserved. Please do not reuse, reproduce, or modify without explicit permission.


