# Customer Churn Analysis (SQL + Python)

## 📌 Project Overview
This project analyzes customer churn behavior for a telecom company to identify the key factors that cause customers to leave the service. The goal is to help the business improve customer retention using data-driven insights.

---

## 📂 Dataset
- Source: Telecom Customer Churn Dataset
- Records: 7,043 customers
- Features: 33 columns including demographics, service usage, billing details, and churn information

---

## 🛠 Tools & Technologies
- Python (Pandas, Matplotlib)
- SQL
- Jupyter Notebook
- Excel Dataset

---

## 🔍 Key Questions Answered
- Which contract type has the highest churn?
- Does higher monthly cost increase churn?
- Do new customers churn more than loyal customers?
- Does technical support affect retention?
- Which payment method is most risky?

---

## 📊 Key Insights

- Month-to-month contract customers had the highest churn rate (~43%)
- Customers paying higher monthly charges were more likely to churn
- New customers (average tenure ~18 months) churned more than long-term customers (~38 months)
- Customers without technical support churned nearly 3x more
- Electronic check users had the highest churn rate (~45%)

---

## 💡 Business Recommendations

- Encourage long-term contracts with discounts
- Review pricing strategy for high-paying customers
- Provide technical support as a standard service
- Promote automatic payment methods
- Improve onboarding for new customers

---

## 📁 Project Structure

customer-churn-analysis/
├── data/
├── notebooks/
├── sql/
├── images/
└── README.md

## 🚀 How to Run

1. Clone the repository
2. Open `notebooks/customer_churn_analysis.ipynb`
3. Install dependencies:
   ```bash
   pip install pandas matplotlib openpyxl
   