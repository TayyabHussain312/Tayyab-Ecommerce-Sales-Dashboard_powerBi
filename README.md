🛒 Tayyab E-Commerce Sales Dashboard (Power BI)

A complete end-to-end Business Intelligence project covering the full workflow from data import to data modeling, DAX measures, and interactive dashboard visualization.

📥 1. Data Import

Loaded raw sales dataset (Orders, Customers, Products, Regions).

Connected through Power BI Desktop using CSV/Excel files.

🧹 2. Data Cleaning

Performed all cleaning steps in Power Query:

Removed duplicated rows

Fixed missing values

Corrected date formats

Standardized category names

Trimmed extra spaces

Converted data types (Date, Whole Number, Decimal)

🔄 3. Data Transformation

Applied transformation steps to prepare analysis-ready tables:

Created new calculated columns

Split columns (e.g., Month, Year, Quarter)

Merged tables using keys

Added custom columns like Profit, Cost, and Sales Amount

Filtered out invalid/zero values

Created a proper calendar table for time intelligence

🧩 4. Data Modeling

Designed a clean Star Schema:

Fact Table: Sales

Dimension Tables: Customers, Products, Categories, State, Calendar

Established one-to-many relationships

Marked Date Table as official Power BI date table

🧮 5. DAX Measures

Created all required measures for dynamic calculations:

KPI Measures

Total Amount

Total Amount = SUM(Sales[Amount])


Total Profit

Total Profit = SUM(Sales[Profit])


Total Quantity

Total Quantity = SUM(Sales[Quantity])


Average Sales

Average Sales = AVERAGE(Sales[Amount])

Time Intelligence

Month Name, Quarter Name

Profit by Month

Year-to-Date Sales (YTD)

📊 6. Data Visualization

Built a fully interactive dashboard using simple, clear visuals.

🔹 KPI Cards (4 KPIs)

💰 Total Amount

📈 Total Profit

📦 Total Quantity

🧮 Average Sales

🔹 Filters / Slicers

🗓 Quarter Slicer

📍 State Slicer

🔹 Visuals

📊 Clustered Bar Chart → Top 10 Sales

📊 Clustered Column Chart → Top 10 Customers

🍩 Donut Chart → Product Quantity by Category

🍩 Donut Chart → Payment Method

📅 Clustered Column Chart → Monthly Profit & Loss

📦 Clustered Bar Chart → Profit by Sub-Category

🎯 7. Project Outcome

This dashboard helps users:

Track high-level performance

Identify best-selling products and customers

Compare profit trends month-wise

Understand category and payment behavior

Filter data by state and quarter

Make quick, data-driven decisions
