# Excel-Sales_Analytics
This project analyzes AtliQ Hardware's sales performance (2019-2021) and Fetch Some important insights from it.

## Project Overview
This project analyzes AtliQ Hardware's sales performance (2019-2021) using ETL processes in Excel/Power Query. It focuses on deriving insights from customer and market data, including growth trends, regional performance, and new customer identification.

1.  **Customer Performance Report** https://github.com/Sam-1799/Excel-Sales_Analytics/blob/main/sales_market_report.pdf                        - Customer-specific net sales (2019-2021) in USD.  
   - Growth percentage (`21 vs 20`) for each customer.  
   - Key columns: `Customer`, `2020 Net Sales`, `2021 Net Sales`, `21 vs 20 %`

2.  **Market Performance vs Target Reported** (https://github.com/Sam-1799/Excel-Sales_Analytics/blob/main/Markets%20Performance%20vs%20Targets%20Reported.pdf)
   - Country-wise net sales (2019-2021) in USD.  
   - Includes 2021 targets and variance analysis.  
   - Key columns: `Country`, `2021 Net Sales`, `2021 Target`, `% Variance`.

---

## Data Cleaning
  - Handling Missing Values
  - Ensure all Dimension Tables contains a unique column.
  - Check Spellings and Replaced it with right.

## Data Modelling
  - Connect Fact Tables with dim tables using Diagram view option in power query inside Measures option.
  - Add a dim_date (Date Table) using power query.
  - Perform and Evaluate the New Measures using DAX Functions.

##Analysis
The analysis answers the following key questions:
1. **Top 10 Products by Sales Growth**: Identifies products with the highest percentage increase in net sales (2020 vs. 2021) (https://github.com/Sam-1799/Excel-Sales_Analytics/blob/main/Top%2010%20Products.pdf)
2. **Division Report**: Presents a breakdown of net sales by division for 2020 and 2021, including growth percentages.
3. **Product Rankings**: Ranks products in the top 5 and bottom 5 based on quantity sold.
4. **New Products in 2021**: Highlights products introduced in 2021 (those with 0% growth in the "21 vs 20" column).
5. **Top Countries by 2021 Sales**: Lists the top 5 countries contributing to net sales in 2021.

    
   
