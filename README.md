Task 3: Data Visualization & Dashboarding

Timeline: 7 Days
Dataset: E-commerce Sales Data (2024-2025)

Objective

Create professional data visualizations and an interactive executive dashboard using Python (Matplotlib, Seaborn, Plotly) and Power BI, based on a cleaned e-commerce sales dataset.


Dataset Overview

ColumnDescriptionOrder IDUnique identifier for each orderOrder DateDate the order was placedCustomer NameName of the customerRegionSales region (North, South, East, West)CityCity of the orderCategoryProduct categorySub-CategoryProduct sub-categoryProduct NameName of the product soldQuantityUnits sold in the orderUnit PricePrice per unitDiscountDiscount appliedSalesTotal sales value for the orderProfitProfit earned on the orderPayment ModePayment method used

Rows: 5,000 orders


Part 1: Python Visualizations (Day 14-15)

Built using pandas, matplotlib, seaborn, and plotly.

Matplotlib
Line Chart — Monthly sales trend (2024-2025)
Bar Chart — Total sales by category
Scatter Plot — Unit price vs. sales
Histogram — Distribution of order sales values


Seaborn
Heatmap — Correlation between Quantity, Unit Price, Discount, Sales, and Profit
Pairplot — Relationships across all numeric fields, segmented by region
Boxen Plot — Sales distribution by category (with outlier detail)


Plotly (Interactive)
Scatter — Unit price vs. sales, colored by category, sized by quantity
Bar — Sales by category and region (grouped)
Line — Monthly sales trend by category


Files
/visualizations
  ├── 01_line_monthly_sales.png
  ├── 02_bar_sales_by_category.png
  ├── 03_scatter_price_vs_sales.png
  ├── 04_histogram_sales_distribution.png
  ├── 05_heatmap_correlation.png
  ├── 06_pairplot_numeric_fields.png
  ├── 07_boxen_sales_by_category.png
  ├── 08_plotly_price_vs_sales.html
  ├── 09_plotly_sales_by_category_region.html
  └── 10_plotly_monthly_trend_by_category.html

How to Run
bashpip install pandas matplotlib seaborn plotly
python visualize_ecommerce.py


Part 2: Power BI Executive Dashboard (Day 16-18)

Dashboard Components
KPI Cards — Total Sales, Total Customers, Total Orders
Sales Trend — Monthly line chart (2024-2025)
Category Breakdown — Donut chart of sales by category
Geographic Map — Sales by region/city
Top 10 Products — Table filtered to highest-selling products
Filter Panel — Slicers for Order Date, Region, and Category


Calculated Measures (DAX)
DAXProfit Margin = SUM(Ecommerce_Sales_Data_2024_2025[Profit]) / SUM(Ecommerce_Sales_Data_2024_2025[Sales])

Tech Stack
Python: pandas, matplotlib, seaborn, plotly
Power BI Desktop (DAX)
Data: CSV (5,000 e-commerce orders, 2024-2025)




Key Insights
(Fill in 2-3 findings from your own charts, e.g., "Electronics generated the highest sales but a lower profit margin than Home Decor, suggesting over-discounting.")
(e.g., "North region consistently outperforms other regions across all quarters.")
(e.g., "Sales peak in [Month], likely tied to seasonal demand.")

