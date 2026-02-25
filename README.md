💳 Credit Card Fraud Detection System
📌 Project Overview

This project detects fraudulent credit card transactions using Machine Learning.
Since fraud detection datasets are highly imbalanced, SMOTE (Synthetic Minority Oversampling Technique) is applied to balance the dataset and improve fraud detection performance.

The project also includes a professional Tkinter GUI Dashboard to display analytics results.

🎯 Problem Statement

Credit card fraud detection is a major financial security challenge.

#The goal of this project is to:

1.Detect fraudulent transactions

2.Handle imbalanced dataset

3.Improve fraud recall

4.Evaluate using Precision & Recall

5.Provide business insights through GUI

📊 Dataset Description

-The dataset contains 5000 synthetic transactions with the following features:

->Transaction_ID

->Customer_ID

->Transaction_Amount

->Transaction_Time

->Merchant_Category

->Location

->Card_Limit

->Current_Balance

->Payment_Due_Date

->Payment_Date

->Num_Transactions_Last_24hrs

->Is_International

->Fraud_Label

⚙️ Technologies Used

~Python

~Pandas

~NumPy

~Scikit-learn

~Imbalanced-learn (SMOTE)

~Matplotlib & Seaborn

~Tkinter (GUI)

🧹 Data Preprocessing

~Datetime conversion

~Feature Engineering:

-On_Time_Payment

-Exceeded_Limit

-Label Encoding

-SMOTE applied for imbalance handling

🤖 Models Used

1️⃣ Logistic Regression
2️⃣ Random Forest (Final Model)

Random Forest performed better in terms of Recall and Precision.

📊 Evaluation Metrics

1.Confusion Matrix

2.Precision

3.Recall (Important for fraud detection)

📈 Business Questions Answered

1.Fraud cases detected correctly

2.Users paying bill on time

3.Recall of fraud class

4.Users exceeding card limit

5.Fraud percentage

6.Fraud-to-normal ratio

7.Precision of fraud class

8.Total transactions

9.Dominant class

10.Highest transaction value

🖥️ GUI Dashboard

The project includes a professional dashboard displaying:

Model performance metrics

Fraud statistics

Customer behavior analytics

▶️ How to Run the Project
✅ Step 1: Clone the Repository
git clone https://github.com/AnnayaSingh/credit-card-fraud-detection.git
cd credit-card-fraud-detection
✅ Step 2: Install Required Libraries

Make sure Python 3.8+ is installed.

Install dependencies:

pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn

Tkinter usually comes pre-installed with Python.

If not:

pip install tk
✅ Step 3: Place Dataset

Make sure the dataset file:

credit_card_fraud_dataset.csv

is inside the project folder.

✅ Step 4: Run the Project
