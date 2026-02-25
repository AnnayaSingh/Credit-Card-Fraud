<!DOCTYPE html>
<html>
<head>
   
<h1>💳 Credit Card Fraud Detection System</h1>

<div class="section">
<h2>📌 Project Overview</h2>
<p>
This project detects fraudulent credit card transactions using Machine Learning.
Since fraud detection datasets are highly imbalanced, 
<span class="highlight">SMOTE (Synthetic Minority Oversampling Technique)</span> 
is applied to balance the dataset and improve fraud detection performance.
</p>
<p>
The project also includes a professional <span class="highlight">Tkinter GUI Dashboard</span> 
to display analytics results.
</p>
</div>

<div class="section">
<h2>🎯 Problem Statement</h2>
<p>Credit card fraud detection is a major financial security challenge.</p>

<h3>The goal of this project is to:</h3>
<ul>
<li>Detect fraudulent transactions</li>
<li>Handle imbalanced dataset</li>
<li>Improve fraud recall</li>
<li>Evaluate using Precision & Recall</li>
<li>Provide business insights through GUI</li>
</ul>
</div>

<div class="section">
<h2>📊 Dataset Description</h2>
<p>The dataset contains 5000 synthetic transactions with the following features:</p>

<ul>
<li>Transaction_ID</li>
<li>Customer_ID</li>
<li>Transaction_Amount</li>
<li>Transaction_Time</li>
<li>Merchant_Category</li>
<li>Location</li>
<li>Card_Limit</li>
<li>Current_Balance</li>
<li>Payment_Due_Date</li>
<li>Payment_Date</li>
<li>Num_Transactions_Last_24hrs</li>
<li>Is_International</li>
<li>Fraud_Label</li>
</ul>
</div>

<div class="section">
<h2>⚙️ Technologies Used</h2>
<ul>
<li>Python</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Scikit-learn</li>
<li>Imbalanced-learn (SMOTE)</li>
<li>Matplotlib & Seaborn</li>
<li>Tkinter (GUI)</li>
</ul>
</div>

<div class="section">
<h2>🧹 Data Preprocessing</h2>
<ul>
<li>Datetime conversion</li>
<li>Feature Engineering:
    <ul>
        <li>On_Time_Payment</li>
        <li>Exceeded_Limit</li>
    </ul>
</li>
<li>Label Encoding</li>
<li>SMOTE applied for imbalance handling</li>
</ul>
</div>

<div class="section">
<h2>🤖 Models Used</h2>
<ul>
<li>Logistic Regression</li>
<li>Random Forest (Final Model)</li>
</ul>
<p>
Random Forest performed better in terms of Recall and Precision.
</p>
</div>

<div class="section">
<h2>📊 Evaluation Metrics</h2>
<ul>
<li>Confusion Matrix</li>
<li>Precision</li>
<li>Recall (Important for fraud detection)</li>
</ul>
</div>

<div class="section">
<h2>📈 Business Questions Answered</h2>
<ol>
<li>Fraud cases detected correctly</li>
<li>Users paying bill on time</li>
<li>Recall of fraud class</li>
<li>Users exceeding card limit</li>
<li>Fraud percentage</li>
<li>Fraud-to-normal ratio</li>
<li>Precision of fraud class</li>
<li>Total transactions</li>
<li>Dominant class</li>
<li>Highest transaction value</li>
</ol>
</div>

<div class="section">
<h2>🖥️ GUI Dashboard</h2>
<p>The project includes a professional dashboard displaying:</p>
<ul>
<li>Model performance metrics</li>
<li>Fraud statistics</li>
<li>Customer behavior analytics</li>
</ul>
</div>

<div class="section">
<h2>▶️ How to Run the Project</h2>

<h3>✅ Step 1: Clone the Repository</h3>
<code>
git clone https://github.com/AnnayaSingh/credit-card-fraud-detection.git<br>
cd credit-card-fraud-detection
</code>

<h3>✅ Step 2: Install Required Libraries</h3>
<p>Make sure Python 3.8+ is installed.</p>

<code>
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
</code>

<p>Tkinter usually comes pre-installed with Python. If not:</p>

<code>
pip install tk
</code>

<h3>✅ Step 3: Place Dataset</h3>
<p>Ensure the file <span class="highlight">credit_card_fraud_dataset.csv</span> is inside the project folder.</p>

<h3>✅ Step 4: Run the Project</h3>

<code>
python fraud_dashboard.py
</code>

<p>
This will train the model, apply SMOTE, evaluate performance, and open the GUI dashboard.
</p>

</div>

</body>
</html>
