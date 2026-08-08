# 📊 E-Commerce Customer Behavior & Segmentation Analysis

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Executive Summary
Understanding customer behavior, lifetime value, and churn indicators is critical for modern e-commerce growth. This project performs an end-to-end analytics workflow on **10,000+ e-commerce customer transaction records**—spanning initial exploratory data analysis (EDA), **RFM (Recency, Frequency, Monetary) Customer Segmentation**, and predictive modeling for customer retention.

---

## 🔑 Key Business Insights

1. **Browsing Time vs. Basket Size:** Extended session duration exhibits low correlation with high transaction value. Strategic direct navigation and targeted product placements drive higher conversion rates than passive browsing.
2. **Discount Sensitivity:** While promotional discounts increase initial transaction volume, average order value (AOV) across discounted vs. non-discounted orders remains largely equivalent.
3. **RFM Segmentation Output:**
   * **Champions (18%):** High monetary contribution, high frequency. Target: Early product access & VIP rewards.
   * **At-Risk (24%):** Formerly active, declining recency. Target: Win-back promotional campaigns.
   * **Hibernating (15%):** Low engagement across all metrics. Target: Low-cost automated email drip sequences.

---

## 🛠️ Project Structure

```text
ecommerce-customer-behavior-analysis/
├── data/
│   └── ecommerce_customer_behavior_dataset.csv
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   └── 02_rfm_segmentation_and_ml.ipynb
├── visuals/
│   ├── customer_segments.png
│   └── correlation_matrix.png
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
