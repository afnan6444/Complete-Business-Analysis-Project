# 📊 Customer Churn Analysis Project

## 📌 Overview
This project analyzes customer churn using a dataset of 500 customers. The goal is to identify key drivers of churn, build predictive models, segment customers, and provide actionable business recommendations to reduce churn and improve customer retention.

---

## 📂 Project Structure
```
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── notebooks/
│   ├── 1_data_cleaning.ipynb
│   ├── 2_eda.ipynb
│   └── 3_analysis.ipynb
├── reports/
│   ├── executive_summary.md
│   └── technical_report.pdf
├── README.md
```

---

## ⚙️ Steps in the Project
1. **Data Cleaning**  
   - Removed duplicates, standardized column names, converted data types.  
   - Normalized `Churn` values (`Yes/No` → 1/0).  
   - Saved cleaned dataset for reproducibility.  

2. **Exploratory Data Analysis (EDA)**  
   - Churn distribution visualization.  
   - Tenure vs churn analysis.  
   - Monthly charges vs churn boxplots.  
   - Correlation heatmap of numeric features.  

3. **Advanced Analysis**  
   - **Logistic Regression:** Predicts churn probability with ~80% accuracy.  
   - **KMeans Clustering:** Segments customers into 3 groups based on tenure and charges.  
   - **Hypothesis Testing:** Validates that higher monthly charges significantly increase churn.  

4. **Insights & Recommendations**  
   - Short‑tenure, high‑charge customers are most at risk.  
   - Month‑to‑month contracts drive churn.  
   - Loyalty discounts, contract incentives, and targeted campaigns recommended.  

---

## 📊 Key Results
- **Churn Rate:** ~26% of customers.  
- **Model Accuracy:** ~80% (Logistic Regression).  
- **Clusters Identified:**  
  1. High risk (short tenure, high charges).  
  2. Moderate risk (medium tenure, moderate charges).  
  3. Low risk (long tenure, stable charges).  
- **Hypothesis Test:** Monthly charges significantly influence churn (p < 0.05).  

---

## 📑 Deliverables
- **Executive Summary (1 page)** → Business‑focused insights.  
- **Technical Report (5–10 pages)** → Detailed methodology, analysis, and recommendations.  
- **Presentation (10–15 slides)** → Visual storytelling for stakeholders.  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/customer-churn-analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run notebooks in order:
   - `1_data_cleaning.ipynb`  
   - `2_eda.ipynb`  
   - `3_analysis.ipynb`  

---

## 📌 Future Work
- Deploy churn prediction model into production (CRM integration).  
- Automate reporting dashboards.  
- Expand dataset for more robust insights.  

