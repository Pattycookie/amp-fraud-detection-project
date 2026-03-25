# aml-fraud-detection-project
AML transaction monitoring project using Python, SQL, and Tableau

# Anti-Money Laundering (AML) Transaction Monitoring Project

## 📌 Project Overview
This project analyzes financial transaction data to identify potential money laundering activities using Python and SQL. The goal is to detect suspicious patterns such as high-value transactions, structuring behavior, and high-frequency accounts, which are common indicators in AML investigations.

---

## 🎯 Objectives
- Identify fraudulent and non-fraudulent transactions
- Detect high-risk transaction patterns
- Analyze structuring behavior (transactions just below reporting thresholds)
- Identify high-frequency accounts
- Build a risk-based classification system

---

## 🛠 Tools & Technologies
- Python (Pandas, Matplotlib)
- SQL (Google BigQuery)
- Tableau (data visualization)
- Jupyter Notebook

---

## 📊 Dataset
- Financial transaction dataset containing transaction details such as:
  - Transaction amount
  - Origin and destination accounts
  - Transaction type
  - Fraud labels

---

## 🔍 Key Analysis Performed

### 1. Fraud vs Non-Fraud Analysis
- Identified class imbalance in the dataset
- Fraud transactions are rare compared to legitimate ones

### 2. High-Value Transactions
- Filtered transactions above a defined threshold (>10,000)
- These transactions are potential risk indicators

### 3. Structuring Detection
- Analyzed transactions between 9,000–10,000
- Identified patterns that may indicate structuring behavior

### 4. High-Frequency Accounts
- Grouped transactions by origin account
- Identified accounts with repeated activity

### 5. Transaction Type Analysis
- Analyzed distribution of transaction types (TRANSFER, CASH_OUT, etc.)

### 6. High-Risk Transaction Filtering
- Combined multiple rules:
  - High transaction amounts
  - High-risk transaction types
- Flagged transactions for further investigation

---

## 📈 Visualizations
- Fraud vs Non-Fraud distribution
- Risk level classification (Low / Medium / High)
- High-risk account analysis
- Transaction type distribution

---

## 📌 Key Findings
- The dataset is highly imbalanced with very few fraud cases
- High-value transactions and specific transaction types are more associated with risk
- Structuring patterns may exist but are subtle in sampled data
- Rule-based risk scoring helps prioritize transactions for investigation

---

## 🚀 Conclusion
This project demonstrates how data analysis techniques can be applied to financial transaction data to support anti-money laundering efforts. It combines rule-based detection with exploratory data analysis to identify suspicious behavior patterns.

---

## 📬 Future Improvements
- Incorporate machine learning models for fraud prediction
- Add time-based anomaly detection
- Expand dataset for more comprehensive pattern detection
- Integrate real-time monitoring systems

---

## 👤 Author
Patricia Louissaint
