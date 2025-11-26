# 🧹 Marketing Data Cleaning & Segmentation

## 📋 Overview
This project demonstrates how to clean and standardize messy marketing data to produce actionable customer segments using RFM analysis and K-Means clustering.

---

## 🎯 Objectives
- Clean and prepare a realistic customer dataset
- Identify and fix inconsistencies, missing values and formatting issues
- Build an explainable RFM segmentation model
- Build a data-driven K-Means clustering model
- Provide marketing recommendations based on customer segmentation

---

## 🧾 Data
- **Source:** [UC Irvine Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Size:** 541,909 records, 8 features
- **Key Variables:** Invoice Quantity, Invoice Date, Unit Price

---

## 🛠 Tools & Methods
- **Languages / Environments:** Python 
- **Libraries:** pandas, numpy, scikit-learn 
- **Techniques:** Data cleaning & validation, duplicate handling, standardization, RFM segmentation, K-Means clustering

---

## 🧩 Process

1. **Data Cleaning**
   - Identified missing, inconsistent and duplicated records
   - Standardized column names and values
   - Enforced consistent and logical data types
   - Created a reproducible cleaning pipeline

2. **Feature Engineering**
   - Create customer-level aggregates: `Recency`, `Frequency` and `Monetary`.

3. **Segmentation**
   - **RFM Segmentation:** Assign each customer Recency, Frequency and Monetary quartiles (1-4) and combined into one score (3-12)
   - **K-Means Clustering:** Clustered customers into three segments using Recency, Frequency and Monetary features
   - **Customer Score:** Created composite score using both RFM Segmentation and K-Means Clustering

4. **Validation & Comparison**
   - Analyze customer profiles by RFM, K and Customer Scores (avg revenue, avg quantity, avg unit price, cancellation rate).

---

## 📈 Key Results
- RFM and K-Means produce valuable but fundamentally different segmentation structures.
- RFM is rule-based and business-friendly.
- K-Means is pattern-based and reveals natural groupings that RFM misses.
- Combining both provides a stronger understanding of customer value.
- Several segments were identified as high-revenue opportunities.
- Customers with high 'customer_score' can be prioritized for more efficient marketing campaigns

---

## 📓 Notebook
👉 [View the full Jupyter Notebook](notebooks/data_cleaning_segmentation.ipynb)

---
## 🧰 Tech Stack
Python • Scikit-learn • Pandas • Jupyter Notebook  

---

## 👤 Author
**Caleb White**  
📫 [LinkedIn](https://linkedin.com/in/calebelwoodwhite) • [GitHub](https://github.com/calebewhite)

