# 📊 Customer Data Analysis for Business Insights

## 📌 Project Overview

This project analyzes customer and transaction data for a mid-sized Indian company to understand customer purchasing behavior, identify high-value customers, and improve customer retention.

Using Python, I performed data cleaning, data processing, exploratory data analysis (EDA), RFM analysis, customer segmentation, and data visualization to generate actionable business insights.

The objective is to help businesses make data-driven decisions, develop targeted marketing strategies, and improve customer engagement and retention.

## 🎯 Business Problem

The company has customer and transaction data but needs a better understanding of its customers. Without proper customer analysis, businesses may struggle with:

- Generic marketing campaigns
- Difficulty identifying high-value customers
- Limited understanding of purchasing behavior
- Customer retention challenges
- Missed opportunities for targeted promotions

This project uses data analytics techniques to address these challenges.

## 🛠️ Tools and Technologies

- **Python** — Data analysis and processing
- **Pandas** — Data cleaning, transformation, and manipulation
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Analysis and documentation

## 📂 Dataset Description

The project uses two datasets:

### 1. Customer Master Data

Contains customer demographic and registration information.

Key columns:
- `CustomerID`
- `Name`
- `Gender`
- `Age`
- `City`
- `MaritalStatus`
- `NumChildren`
- `JoinDate`

### 2. Customer Transactions

Contains customer purchase transaction information.

Key columns:
- `CustomerID`
- `TransactionDate`
- `TransactionAmount`

### Dataset Size

| Dataset | Records | Columns |
|---|---:|---:|
| Customer Master Data | 1,000 | 9 |
| Customer Transactions | 23,050 | 3 |

*These counts are based on the data-loading outputs in the project notebook.*

## 🔄 Project Workflow

1. Import Python libraries
2. Load customer and transaction datasets
3. Understand the data structure and data types
4. Clean and validate the datasets
5. Check missing values and duplicate records
6. Convert date columns into appropriate date formats
7. Merge customer and transaction data
8. Perform exploratory data analysis
9. Calculate Recency, Frequency, and Monetary (RFM) metrics
10. Score and segment customers
11. Create visualizations
12. Generate business insights and recommendations

## 📈 RFM Analysis

RFM analysis is used to understand customer purchasing behavior through three metrics:

- **Recency (R):** How recently a customer made a purchase.
- **Frequency (F):** How frequently a customer makes purchases.
- **Monetary (M):** How much a customer spends.

These metrics help identify valuable customer groups and support more targeted marketing decisions.

## 📊 Analysis and Visualizations

The project focuses on:

- Customer demographic analysis
- Transaction and spending analysis
- Customer purchasing behavior
- RFM calculation and scoring
- Customer segmentation
- Visual exploration of customer trends
- Business insights for marketing and retention

## 💡 Business Applications

The analysis can help businesses:

- Identify high-value customers
- Design targeted marketing campaigns
- Improve customer retention strategies
- Create personalized promotional offers
- Understand customer spending patterns
- Support data-driven business decisions

## 🚀 How to Run This Project

### Prerequisites

Install Python and the required libraries.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Steps

1. Clone or download this repository.
2. Ensure the required customer and transaction CSV files are available in the expected project directory.
3. Open the project notebook in Jupyter Notebook.
4. Verify that the dataset file paths match your local folder.
5. Run the notebook cells in order.

## 📁 Repository Structure

```text
Python-Data-Analysis-Project/
│
├── README.md
├── Python_Project_Megha.html
├── Python_Project_Megha.ipynb
├── Customer_Master_Data.csv
└── Customer_Transactions.csv
```

*The structure above is a suggested layout. Include only files that you have actually uploaded and are permitted to share.*

## 👩‍💻 Author

**Megha Vasava**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

This project demonstrates my learning in Python-based data analysis, customer segmentation, data visualization, and business insight generation.

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.
