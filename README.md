# Superstore Customer Intelligence & Profitability Analysis

An end-to-end retail analytics project using SQL, Python, and Tableau to investigate sales performance, profitability, customer purchasing behavior, and customer segmentation.

## Project Overview

This project analyzes the Superstore retail dataset to explore business performance and customer behavior. The objective is to transform transaction-level data into meaningful business insights through data preparation, analytical queries, customer metrics, and interactive dashboards.

The project combines SQL for structured business analysis, Python for data processing and analytical validation, and Tableau for visualization and data storytelling.

## Business Questions

- Which product categories and regions generate the most sales and profit?
- Which customers contribute most to revenue and profitability?
- How many customers make repeat purchases?
- How do sales, profit, and profit margins change over time?
- How can RFM analysis help identify different customer groups?
- How do discounts relate to product profitability?

## Tools & Technologies

| Tool           | Purpose                                                                        |
| -------------- | ------------------------------------------------------------------------------ |
| MySQL 8+       | Data quality checks, SQL analysis, KPI calculations, and customer segmentation |
| Python         | Data preparation, exploratory analysis, customer metrics, and validation       |
| Pandas & NumPy | Data manipulation and numerical analysis                                       |
| Matplotlib     | Analytical visualizations                                                      |
| Tableau        | Interactive dashboards and business insights                                   |
| GitHub         | Version control and project documentation                                      |

## Tableau Dashboards

### 1. Superstore Sales & Profitability Dashboard



Explores sales and profitability across regions, product categories, and other business dimensions.

### 2. Customer Intelligence & Insights Dashboard



Focuses on customer purchasing behavior, repeat customers, RFM segmentation, customer profitability, and revenue trends.

## Analytical Methods

### Data Quality & Preparation

- Inspect dataset structure and missing values.
- Validate data types, dates, and numerical fields.
- Prepare data for consistent analysis.

### Sales & Profitability

- Total sales, total profit, and profit margin.
- Regional and product category performance.
- Discount analysis and profitability comparisons.
- Sales trends and year-over-year growth.

### Customer Analytics

- Customer-level sales and profitability.
- Repeat customer analysis.
- Top customer contribution to total sales.
- Average customer sales and average order value.

### RFM Customer Segmentation

- **Recency:** how recently a customer purchased.
- **Frequency:** how often a customer placed orders.
- **Monetary value:** the total sales associated with a customer.

RFM analysis is used to classify customers into behavioral groups and support targeted business recommendations.

## Repository Structure

```text
superstore-customer-intelligence/
├── data/
│   ├── _superstore.xls
│   └── README.md
├── images/
│   ├── superstore-sales-dashboard.png
│   ├── customer-insights-dashboard.png
│   └── README.md
├── python/
│   ├── superstore_customer_analysis.ipynb
│   └── README.md
├── sql/
│   ├── 03_SQL_Customer_Revenue_Analysis_FIXED.sql
│   └── README.md
└── README.md
```

## How to Reproduce the Analysis

1. Obtain the Superstore dataset and identify the `Orders` worksheet.
2. For SQL analysis, use MySQL 8+ and import the source data into a table named `superstore`.
3. Review the SQL script before running it. It creates a cleaned table named `superstore_clean` and replaces an existing table with that name.
4. Open the Python notebook in Jupyter or Google Colab and provide the dataset when prompted.
5. Open the packaged Tableau workbook in Tableau Desktop and check its data connections.

## Data Validation

A key objective is to reconcile the core metrics across SQL and Python, then confirm that the Tableau dashboards use consistent definitions.

The validation process covers row counts, distinct orders, distinct customers, sales, profit, profit margin, and customer metrics. Numerical findings should be reported only after the relevant calculations have been successfully executed and checked.

## Skills Demonstrated

- SQL querying and business KPI analysis
- Data quality assessment and preparation
- Python data analysis
- Customer analytics and RFM segmentation
- Profitability and sales performance analysis
- Tableau dashboard development
- Analytical documentation and business problem-solving

---

**Project focus:** Turning retail transaction data into actionable insights about customers, sales, and profitability.
