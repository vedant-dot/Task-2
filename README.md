1. Load the Data
Open Power BI Desktop.

Click Home > Get Data > Excel.

Select sales_data_sample.xlsx.

Choose the relevant sheet (usually named Orders, Sales, Sheet1, etc.).

Click Load.

2. Data Cleaning (if needed)
Open Power Query Editor (Transform Data).

Ensure columns like OrderDate, Product, Region, Sales, Quantity, and Profit are properly formatted.

Rename columns for clarity if needed.

Click Close & Apply.

3. Create Visual Report (Dashboard)
🔹 Page 1: Sales Overview
Card 1: Total Sales (SUM(Sales))

Card 2: Total Quantity (SUM(Quantity))

Card 3: Total Profit (SUM(Profit))

Add Text Box for Title: “Executive Summary – Sales Performance”

🔹 Page 2: Regional Sales
Visual: Map or Bar Chart

X-axis: Region

Y-axis: SUM(Sales)

Add tooltip: % of Total Sales

Insight: Identify top and low-performing regions.

🔹 Page 3: Top Products
Visual: Horizontal Bar Chart

Axis: Product

Value: SUM(Sales)

Filter: Top 10 by value.

Insight: Show contribution of top products.

🔹 Page 4: Sales Trend Over Time
Visual: Line Chart

Axis: OrderDate (monthly/quarterly aggregation)

Value: SUM(Sales)

Insight: Detect seasonality and sales spikes.

🔹 Page 5: Profitability by Category
Visual: Clustered Column Chart

Axis: Product Category

Values: SUM(Sales) and SUM(Profit)

Insight: Spot high-revenue, low-profit categories.

🔹 Page 6: Customer Breakdown
Visual: Pie Chart or Donut Chart

Legend: Customer Type or Channel

Value: SUM(Sales)

Insight: Segment customer base and revenue drivers.
