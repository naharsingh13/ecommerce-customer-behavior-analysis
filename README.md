# E-Commerce Customer Behavior Analysis

## Project Overview

This project analyzes e-commerce customer transaction data to understand purchasing behavior, customer value, sales patterns, customer segmentation, and retention.

The analysis uses Python-based exploratory analysis, RFM (Recency, Frequency, Monetary) analysis, customer segmentation, purchase trends, and cohort retention analysis to generate actionable business recommendations.

## Objectives

- Clean and prepare customer transaction data
- Perform exploratory data analysis
- Analyze purchase and sales trends
- Identify high-value and at-risk customers using RFM analysis
- Segment customers based on RFM scores
- Analyze customer retention using cohort analysis
- Translate analytical findings into business recommendations

## Dataset

The project uses an e-commerce customer transaction dataset containing **250,000 transaction records** and **13 original columns**.

After cleaning, the analysis works with **250,000 records and 12 columns**.

The dataset contains customer, purchase, product, payment, demographic, and transaction-related information.

> The raw CSV is not included in this repository by default. Place the CSV in the Colab/runtime environment when running the notebook.

## Key Analysis

### 1. Data Quality & Cleaning

The project checks:

- Dataset dimensions
- Column information
- Missing values
- Duplicate records
- Date validity

Cleaning includes:

- Converting `Purchase Date` to datetime
- Handling missing `Returns`
- Removing the duplicate `Age` column
- Removing records with invalid purchase dates

### 2. Feature Engineering

Date-based features are created for:

- Purchase year
- Purchase month
- Purchase day
- Day of week
- Purchase hour
- Day name
- Month name

### 3. Exploratory Data Analysis

The notebook explores:

- Product category sales
- Customer age distribution
- Payment methods
- Monthly sales trends
- Sales by day of week

### 4. RFM Customer Analysis

Customers are evaluated using:

- **Recency:** how recently a customer purchased
- **Frequency:** number of purchases
- **Monetary:** total purchase amount

The analysis identifies **49,673 unique customers**.

### 5. Customer Segmentation

Customers are grouped using combined RFM scores into:

- Champions
- Loyal Customers
- Potential Loyalists
- Customers Needing Attention
- At Risk

The largest segment in the analysis is **At Risk**, with **13,376 customers (26.9%)**.

### 6. Cohort & Retention Analysis

Cohort analysis tracks customers from their first purchase month and measures retention over subsequent months.

The analysis reports an average second-month retention of approximately **10.3%** across the available cohorts.

## Key Findings

- **At Risk** is the largest customer segment, representing approximately **26.9%** of analyzed customers.
- **Books** generated the highest total sales in the analysis, approximately **₹204.94 million**.
- **Credit Card** was the most frequently used payment method, with **100,486 transactions**.
- Cohort analysis indicates approximately **10.3% average second-month retention**.

## Business Recommendations

1. Prioritize retention and reactivation campaigns for At Risk customers.
2. Reward Champions and Loyal Customers through loyalty benefits and personalized offers.
3. Use targeted offers to convert Potential Loyalists into Loyal Customers.
4. Use high-performing product categories for cross-selling and promotional campaigns.
5. Monitor cohort retention to identify where customer engagement declines.
6. Optimize the checkout experience around commonly used payment methods.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Project Structure

```text
customer-behavior-analysis/
│
├── Customer_Behavior_Analysis.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Open the notebook in Google Colab.
2. Run the first cell.
3. Upload the required CSV dataset when prompted.
4. Run the notebook from top to bottom.
5. Review the generated tables, charts, segmentation results, retention analysis, and recommendations.

## Portfolio Value

This project demonstrates practical skills in:

- Data cleaning
- Exploratory data analysis
- Feature engineering
- Customer analytics
- RFM modeling
- Customer segmentation
- Cohort retention analysis
- Data visualization
- Business-oriented analytical thinking

## Author

**Sunpreet Singh**

B.Tech Computer Science
