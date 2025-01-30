# ASCES SALES DASHBOARD

### Dashboard Link : https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection

## Problem Statement

ASCES SOUND  is a leading innovator in audio technology and sell high end audio equipment. This is a Product Analytics dashboard that shows:
 
a. Revenue by Country: Top-performing regions with corresponding revenue.

b. Revenue by Date and Year: Comparative Trends

c. Revenue breakdown by Discount Bands: Distribution of Revenue across different discount categories

d. Detailed Table View


### Steps followed 

- Step 1 : Create database in Microsoft SQL Server
- Step 2 : Create tables for Product Sales, Product Data and Discount Data
- Step 3 : Calculate Revenue and Total Cost .
- Step 4 : Join Product Sales and Product Data using Product ID.
- Step 5 : Create cte (temporary database) to hold the new joined database.
- Step 6 : Calculate Product Discount and apply it to Revenue.  
- Step 7 : JOIN the cte to Discount data tabe using months of the year.
- Step 8 : Import database to Power BI for visualization.
- Step 9 : Add a card visual showing the different products sold by the company.

        The product url was used to display a visual of the product.

- Step 10 : Add a card visual showing product description
- Step 11 : Add a bar chart showing revenue by country 
- Step 12: Add a column chart showing revenue by year
- Step 13: Add a donut chart showing revenue by discount rate
- Step 14: Create a new table called Profit in Power Query 
        
        Created custom table where Profit=Revenue - Discount

- Step 14 : Created a table visual displaying Profit and Revenue by Product and Country over the two years

# Snapshot of Dashboard (Power BI Service)

![Image](https://github.com/user-attachments/assets/c77034f6-b8af-4ea3-a4df-ac9ab6c47b57)

 
 
# Insights

1. Most popular month for sales is in June across all product categories
2. Most popular selling product is the Scarlett 2i2
3. The majority od sales were in Canada followed closey by the United States
4. Profit increased by 8.7% across the two years
