💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions.
This project uses Python, Scikit-learn, and a highly imbalanced dataset to train and evaluate models for fraud detection.


📊 Features

✅ Exploratory Data Analysis (EDA)

✅ Data preprocessing & scaling

✅ Handling imbalanced classes (e.g., SMOTE, under/oversampling)

✅ Training ML models:

  - Logistic Regression
  
  - Random Forest
  
  - XGBoost

✅ Evaluation metrics:

  - Confusion Matrix
  
  - ROC-AUC Curve
  
  - Precision, Recall, F1-Score

✅ Visualization of results


🚀 Getting Started

🔷 Prerequisites

Python ≥ 3.7

pip

git (optional, for GitHub uploads)


🔷 Install dependencies

Clone the repository and install requirements:

git clone https://github.com/your-username/Credit_Card_Fraud_Detection.git

cd Credit_Card_Fraud_Detection

pip install -r requirements.txt

Or, if you’re running notebooks interactively:

jupyter notebook


📈 Example Outputs

✅ Confusion Matrix:

[[85000   10]

 [   25  120]]

✅ Classification Report:

              precision    recall  f1-score   support

    Genuine       0.999    0.999    0.999    85010

     Fraud       0.923    0.828    0.873      145

   accuracy                           0.999    85155
  
  macro avg       0.961    0.914    0.936    85155

weighted avg       0.999    0.999    0.999    85155

✅ ROC-AUC Score:

0.981

(Replace with your actual numbers if you have different results.)


📚 Dataset

We use the Credit Card Fraud Detection Dataset

284,807 transactions

492 frauds

Highly imbalanced (~0.172% fraud)
