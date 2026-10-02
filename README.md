# Online Retail Sales & Customer Analytics

## Project Overview

This project analyzes an online retail transaction dataset to identify sales trends, customer behavior, geographic performance, and transaction cancellations.

The analysis was performed using Python and Pandas, and the results were visualized through an interactive Power BI dashboard.

## Business Problem

The business needs to understand:

- Overall sales and revenue performance
- Monthly sales trends
- Top-performing countries and products
- Customer revenue contribution
- Transaction cancellation patterns
- Key areas for business improvement

## Objectives

- Clean and prepare the retail transaction data
- Analyze sales and customer data
- Identify important business trends
- Calculate key performance indicators
- Build an interactive Power BI dashboard
- Generate actionable business insights

## Dataset

**Dataset:** UCI Online Retail Dataset

The dataset contains online retail transactions with information such as:

- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

The original dataset contained 541,909 records.

After removing duplicate records, the cleaned dataset contained 536,641 records.

The cleaned dataset is approximately 68 MB and is not included in this repository due to GitHub's browser upload file-size limitation.

## Data Cleaning

The following preprocessing steps were performed using Python/Pandas:

- Checked dataset structure and data types
- Identified missing values
- Removed duplicate records
- Identified cancelled transactions
- Created transaction status
- Calculated revenue
- Calculated cancellation amount
- Created year and month fields
- Filtered valid sales transactions
- Prepared the cleaned dataset for analysis and Power BI

## Analysis Performed

The analysis focused on:

### Sales Analysis

- Total Revenue
- Total Orders
- Total Quantity
- Average Order Value
- Monthly Revenue
- Country-wise Revenue
- Product-wise Revenue

### Customer Analysis

- Total Customers
- Customer Revenue
- Top Customers
- Revenue per Customer

### Transaction Analysis

- Cancelled Orders
- Cancellation Value
- Cancellation Rate
- Monthly Cancellation Trends
- Country-wise Cancellation Value

## Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Revenue | £10.64M |
| Total Orders | 19,960 |
| Total Quantity | 5.57M |
| Average Order Value | £533.17 |
| Total Customers | 4,338 |
| Cancelled Orders | ~5K |
| Cancellation Value | £893.98K |
| Cancellation Rate | 25.91% |
| Revenue per Customer | £2.45K |

## Power BI Dashboard

The Power BI dashboard contains two main pages:

### 1. Online Retail Sales & Customer Analytics

Includes:

- Revenue KPI
- Orders KPI
- Quantity KPI
- Average Order Value
- Customer KPI
- Monthly Revenue Trend
- Top Countries by Revenue
- Top Products by Revenue
- Year and Country filters

### 2. Customer & Transaction Insights

Includes:

- Cancelled Orders
- Cancellation Value
- Cancellation Rate
- Revenue per Customer
- Monthly Cancellation Value
- Cancellation Value by Country
- Customer Revenue Distribution
- Top Customers by Revenue
- Country, Year and Transaction Status filters

## Key Business Insights

- The United Kingdom contributes the majority of overall revenue.
- Revenue shows noticeable variation across months, with November showing a major peak.
- A relatively small group of customers contributes a significant portion of revenue.
- The analysis shows substantial transaction cancellation activity.
- Customer-level analysis helps identify high-value customers for retention strategies.
- Geographic and monthly trends can support inventory and operational planning.

## Business Recommendations

- Focus on retaining high-value customers through targeted engagement.
- Prepare inventory and operations for high-demand periods.
- Investigate major cancellation patterns to identify operational issues.
- Continue monitoring country-level sales performance.
- Analyze merchandise products separately from non-merchandise transaction entries.

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI
- Microsoft Excel

## Project Structure

```text
online-retail-sales-customer-analytics/
│
├── data/
│   └── README.md
│
├── Power BI/
│   └── Retail Analysis dashboard.pbix
│
├── Python/
│   └── Data Cleaning,pre-processing and Analysis.ipynb
│
├── Report/
│   └── Online Retail Business Report.docx
│
├── screen shot/
│   ├── Customer & Transaction Insights.png
│   └── Online Retail Sales & customer Analytics.png
│
└── README.md
```
