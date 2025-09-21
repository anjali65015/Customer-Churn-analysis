# Customer Churn Analysis

This project analyzes customer churn in a telecommunications company to identify the key factors influencing churn and provide insights to improve customer retention strategies.

---

## 📌 Executive Summary
The analysis explores the **Telco Customer Churn dataset**, focusing on customer demographics, contract types, service usage, and payment methods. The aim is to highlight high-risk customer segments and suggest actionable strategies to reduce churn.

---

## 🔑 Key Findings

### Overall Churn Rate & Demographics
- **Churn Rate:** ~26.54% (1,869 customers) churned, while 73.46% (5,174 customers) stayed.
- **Gender:** Similar churn distribution between male and female customers → gender is not a strong predictor.
- **Senior Citizens:** Significantly higher churn (41.7%) compared to non-senior citizens (23.6%).

### Service Usage & Contracts
- **Contract Type:**  
  - Month-to-month → 43.3% churn.  
  - One-year → 11.3% churn.  
  - Two-year → 2.8% churn.  
  → Longer-term contracts drastically reduce churn.
- **Tenure:**  
  - New customers (1–2 months) have highest churn.  
  - Long-tenure customers (60+ months) are highly loyal.
- **Payment Method:**  
  - Electronic checks → 45.3% churn (highest).  
  - Other payment methods (credit card, bank transfer, mailed checks) show much lower churn.
- **Service Subscriptions:**  
  - Fiber Optic internet users → 41.9% churn (higher than DSL at 18.9%).  
  - Lack of Online Security or Tech Support services increases churn risk.

---

## 🎯 Conclusion
The analysis identifies the following **high-risk segments**:
- Month-to-month contract customers  
- New customers with short tenure  
- Customers paying via electronic checks  
- Senior citizens  
- Fiber Optic internet users without Online Security/Tech Support  

### Recommended Strategies:
- Encourage migration to longer-term contracts  
- Improve onboarding experience for new customers  
- Offer bundled services (e.g., Online Security, Tech Support)  
- Provide incentives for secure payment methods  
- Special retention focus on senior citizens  

---

## 📂 Project Files
- `TCA.ipynb` → Jupyter Notebook with full analysis  
- `customer-churn.csv` → Dataset used  
- `Telco Customer Churn analysis.pdf` → Detailed project report  

---

## 🚀 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- **Jupyter Notebook** for analysis and visualization  

---

## 📖 Reference
Based on the **Telco Customer Churn dataset** used for exploratory data analysis and predictive modeling.  

---
