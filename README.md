Deployed Link: https://ccfdai.streamlit.app/

**💳 Credit Card Fraud Detection using Machine Learning**

 **Project Overview**
 
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Credit card fraud is a serious financial issue, and early detection can significantly reduce losses for financial institutions and customers.
In this project, we trained and compared multiple classification models to identify fraudulent transactions and built a user-friendly web interface using Streamlit for real-time prediction.

**Objective**

Detect whether a credit card transaction is Fraudulent or Genuine
Compare different ML models and select the best-performing one
Build an interactive UI for real-time fraud prediction

**Dataset**

Source: Kaggle – Credit Card Fraud Detection Dataset
The dataset contains anonymized transaction data.
Features include:
Time
Amount
V1 to V28 (PCA-transformed features)
Target Variable:
0 → Genuine Transaction
1 → Fraudulent Transaction
⚠️ The dataset is highly imbalanced, with fraud cases representing a very small percentage of total transactions.

**Technologies Used**

Python
Pandas
NumPy
Matplotlib & Seaborn
Scikit-learn
Streamlit

**Models Implemented**

1️⃣ Logistic Regression
Used as a baseline model.
Provided good performance but struggled slightly with non-linear decision boundaries.

2️⃣ Decision Tree Classifier  (Final Model)
Captures complex patterns in data.
Performed better than Logistic Regression.
Selected as the final deployed model.

**Key Insights**

Fraud detection requires more focus on Recall than Accuracy due to class imbalance.
Decision Tree handled the non-linear relationships in transaction data more effectively.
A user-friendly interface improves real-world usability of ML systems.

**Example:**
 <img width="1585" height="752" alt="image" src="https://github.com/user-attachments/assets/60727279-3257-42f0-9c65-484770afa322" />
 <img width="1622" height="772" alt="image" src="https://github.com/user-attachments/assets/51ed79dd-37c1-4a59-8cf8-326f384c3100" />


