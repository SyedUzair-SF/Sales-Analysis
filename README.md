# Regional Sales Analysis

## Objective
Analyze 5 years of U.S. regional sales data to identify revenue trends, seasonal patterns, product performance, channel profitability, and regional differences, and present insights through analysis and dashboards.

## Dataset
- Sources:
  - Regional Sales Dataset.xlsx
  - Sales_data.csv
- Scope:
  - ~64,000 sales transactions
  - 175 customers, 30 products, 4 U.S. regions
- Key fields:
  - Order date, region, product, customer, quantity, revenue, cost, profit, margin, channel

## Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook
- Excel
- Power BI
- Matplotlib, Seaborn

## Project Workflow
1. Data loading from multiple Excel and CSV files  
2. Data cleaning and validation (no missing values or duplicates)  
3. Merging sales, customer, product, region, and budget tables  
4. Feature creation (profit, profit margin %, time-based fields)  
5. Exploratory Data Analysis (EDA)  
6. KPI analysis and visualization  
7. Power BI dashboard creation  

## Analysis Performed
- Exploratory Data Analysis (EDA)
- Revenue and profit trend analysis
- Seasonal pattern identification
- Product and SKU performance analysis
- Channel-wise revenue and margin comparison
- Regional and state-level performance analysis
- Customer contribution and segmentation analysis
- Correlation analysis of pricing, revenue, cost, and profit

## Key Insights
- Clear seasonality observed, with revenue peaks in late spring and early summer and dips around January–April  
- Products 26 and 25 contribute a significant share of total revenue, indicating SKU concentration  
- Wholesale channel drives the majority of sales volume, while Export channel shows higher profit margins  
- West region leads in revenue, with noticeable regional performance differences  
- Revenue is highly correlated with unit price, while quantity shows weaker correlation  

## Power BI Dashboard
An interactive Power BI dashboard was built to visualize:
- Revenue and profit KPIs
- Regional and state-level sales performance
- Product and channel contribution
- Customer segmentation and margin analysis  

File:
- `SALES REPORT.pbix`

## Files in This Repository
- `EDA_Regional_Sales_Analysis.ipynb` – Exploratory data analysis notebook  
- `Regional Sales Dataset.xlsx` – Source dataset  
- `Sales_data.csv` – Processed/cleaned data export  
- `SALES REPORT.pbix` – Interactive Power BI dashboard  
- `Regional-Sales-Analysis.pptx` – Project presentation  
- `Regional-Sales-Analysis Project Report.pdf` – Detailed project report  

## Outcome
This project demonstrates an end-to-end data analytics workflow, from raw data preparation and EDA to dashboarding and insight generation, focused on practical sales and business analysis use cases.
