# 📊 Financial Risk Analysis – Barclays (Data Science Project)

## 📌 Project Overview
This project focuses on **financial transaction analysis and risk identification** using real-world styled banking data inspired by **Barclays**.  
The goal is to clean raw transaction data, analyze customer behavior, identify risky patterns, and derive actionable insights using **Python, Pandas, and Data Visualization techniques**.

---

## 🎯 Objectives
- Clean and preprocess raw financial transaction data  
- Perform descriptive transaction analysis (monthly & yearly trends)
- Identify top & bottom performing accounts
- Build customer profiles and activity segments
- Detect potential **financial risk indicators**
- Visualize insights clearly for business understanding
- Validate assumptions using **hypothesis testing**

---

## 🗂 Dataset Description
The dataset contains banking transaction-level information such as:
- Customer & Account details
- Transaction types (Deposit, Withdrawal, Transfer, Payment)
- Transaction amount & account balance
- Risk score, credit rating, and tenure
- Date & regional metadata

> 📌 *Note: This dataset is used strictly for academic and learning purposes.*

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **SciPy (Statistical Testing)**
- **Jupyter Notebook**

---

## 🧩 Project Workflow

### 🔹 Task 1: Data Cleaning & Formatting
- Removed currency symbols and invalid characters
- Converted transaction amounts to numeric values
- Handled missing values and invalid dates
- Standardized categorical fields

---

### 🔹 Task 2: Descriptive Transaction Analysis
- Monthly & yearly transaction summaries
- Credit vs Debit trend analysis
- Identification of top & bottom performing accounts
- Dormant/inactive account detection (gap > 60 days)

---

### 🔹 Task 3: Customer Profile Building
- Account activity segmentation (Low / Medium / High)
- Customer segmentation based on:
  - Average balance
  - Average transaction amount
- Identification of:
  - High inflow accounts
  - High-frequency low-balance accounts
  - Negative balance accounts

---

### 🔹 Task 4: Financial Risk Identification
- Detection of unusually large withdrawals (95th percentile)
- Balance volatility analysis (standard deviation)
- Outlier detection using **IQR method**
- Flagging anomalous transactions

---

### 🔹 Task 5: Data Visualization
- Monthly credit vs debit trend line chart
- Bar charts for top-performing accounts
- Heatmap for transaction volume
- Boxplot for transaction distribution
- Scatter plots for customer behavior analysis
- Pie chart for account type distribution

---

### 🔹 Task 6: Hypothesis Testing
**Hypothesis Tested:**  
> Do high-volume transaction accounts have significantly higher average balances than low-volume accounts?

- Used **Levene’s Test** for variance check  
- Applied **Welch’s t-test**
- Calculated **Cohen’s d** for effect size  

📌 **Result:**  
No statistically significant difference found between high-volume and low-volume account balances.

---

### 🔹 Task 7: Video Presentation
🎥 Project Explanation Video:  
👉 https://www.loom.com/share/56af54df97dd4a28967712c26e668c42

---

## 📈 Key Insights
- Certain accounts show high transaction volume but low balance → potential risk
- Large withdrawals cluster around specific accounts
- Transaction activity is seasonally influenced
- Balance volatility is a strong risk indicator

---

## 🚀 How to Run the Project
1. Clone the repository  
```bash
git clone https://github.com/your-username/financial-risk-analysis-barclays.git
