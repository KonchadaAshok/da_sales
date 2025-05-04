1. Load CSV File
Open Tableau

Click "Text File", and load cleaned_superstore_sales.csv

2. Create Visuals
a. Monthly Sales Trend

Chart Type: Line Chart

Columns: Order Month

Rows: SUM(Sales)

b. Sales by Region

Chart Type: Bar or Map

Rows: Region

Columns: SUM(Sales)

c. Top Products

Chart Type: Horizontal Bar Chart

Rows: Product Name

Columns: SUM(Sales)

Filter: Top 10 by Sales

d. Filters (Interactive)
Drag these to Filters shelf or as Dashboard filters:

Region

Category

Order Month

e. KPI Cards (Optional)

Use labels or cards for: SUM(Sales), SUM(Profit), COUNTD(Order ID)
