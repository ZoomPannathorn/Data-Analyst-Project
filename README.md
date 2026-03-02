# Scam-Induced Transaction Detection

## 📊 Project Overview
This project analyzes financial transaction data to identify mule transaction behavior and fraud risk patterns. 
The entire data cleaning and preparation process was performed independently before analysis and dashboard development.

---

## 🎯 Business Objective
- Detect behavioral signals of mule accounts
- Identify high-risk transaction characteristics
- Validate the effectiveness of risk scoring
- Translate data insights into actionable monitoring strategies

---

## 🧹 Data Cleaning Process (Performed Independently)

Raw transaction data required preprocessing before analysis. The following steps were completed in Excel:

- Removed duplicate transaction records
- Handled missing values
- Standardized transaction time format
- Created `late_night_flag` feature
- Calculated `time_gap_previous_transaction`
- Validated binary fields (0/1 consistency)
- Cleaned inconsistent categorical values
- Verified total transaction counts

This step ensured data accuracy and reliability before modeling and visualization.

---

## 🛠 Tools & Technologies
- Excel (Data Cleaning & Feature Engineering)
- Python (Google Colab – Risk Analysis & Validation)
- Power BI (Dashboard & Visualization)
- GitHub (Version Control)

---
---

## 📊 Dashboard Structure

### 1️⃣ Executive Overview
<img width="1263" height="697" alt="image" src="https://github.com/user-attachments/assets/621dc4fb-dde2-4f87-949c-4809ebf08f7e" />
High-level summary of transaction activity and fraud exposure.
- Total Transactions
- Mule Transaction %
- Average Transaction Amount
- Average Transaction Gap
- Transaction Distribution (Mule vs Non-Mule)
- Risk Score Effectiveness Overview

Purpose: Provide management-level visibility into overall fraud exposure.

---

### 2️⃣ Behavioral Pattern Analysis
<img width="1263" height="702" alt="image" src="https://github.com/user-attachments/assets/1a1f96f7-dafc-4a21-b1ec-3501506f04a9" />
Focused analysis of transaction behavior patterns.
- Fraud Risk Score Distribution
- Rapid Transaction Intervals
- Late-Night Transaction Activity
- High Transaction Amount as Risk Indicator

Purpose: Identify behavioral signals associated with mule accounts.

---

### 3️⃣ Fraud Pattern Deep Dive
<img width="1302" height="730" alt="image" src="https://github.com/user-attachments/assets/3322bc09-0d3b-4b25-a131-f6f9a27f7680" />
Detailed investigation into suspicious accounts and risk relationships.
- Time Pattern Trend Analysis
- Risk Model Evaluation (Confusion Matrix Style)
- Top Risk Accounts
- Risk Score vs Transaction Amount Relationship

Purpose: Validate model effectiveness and identify high-risk entities.

## 🔎 Key Analyses

### 1️⃣ Rapid Transaction Interval Analysis
Identified burst transaction behavior within short time gaps.

### 2️⃣ Late-Night Behavioral Pattern
Analyzed hourly distribution of mule transactions.

### 3️⃣ High Transaction Amount Risk Analysis
Binned transaction amounts to evaluate fraud likelihood.

### 4️⃣ Risk Score Distribution Validation
Assessed how effectively the risk score differentiates mule vs non-mule accounts.

---

## 📊 Key Insights
- Mule accounts demonstrate rapid, high-frequency transaction bursts
- Late-night activity is strongly associated with mule behavior
- High transaction amounts increase fraud probability
- Risk scoring aligns effectively with suspicious behavior

---

## 🧠 Executive Insights

- Mule transactions represent a small percentage (~2%) but exhibit distinct behavioral patterns.
- Rapid transaction bursts and short time gaps strongly correlate with mule activity.
- High transaction amounts significantly increase fraud likelihood.
- Risk scoring model demonstrates strong separation between normal and suspicious behavior.
- Targeted monitoring on late-night high-value transactions can improve fraud detection efficiency.

---

## 🚀 Project Workflow
1. Raw Data Collection
2. Data Cleaning & Feature Engineering (Excel)
3. Exploratory Data Analysis
4. Risk Pattern Validation (Python)
5. Dashboard Development (Power BI)

---

## 📌 Conclusion
This project highlights the importance of structured data cleaning and behavioral analytics in fraud detection. Accurate preprocessing significantly improved analysis reliability and insight quality.



---

## 👤 Author
Pannathorn Suvannasai  
Data Analyst | Data Engineering Student
