# Interactive Sales & Profit Performance Dashboard — Global Superstore

## Project Overview
This project is an interactive **Power BI dashboard** built using the **Global Superstore dataset**.  
The goal is to analyze **sales, profit, customer performance, and segment-wise trends** using dynamic filters and business KPIs.

The dashboard allows stakeholders to quickly answer:
- How are sales and profit performing overall?
- Which regions, categories, and customers drive the most revenue?
- How do sales trend over time?
- Who are the top contributors to sales?

---

## Tools & Technologies
- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Global Superstore Dataset (CSV)**

---

## Dataset
**Global Superstore Dataset**  
Contains order-level sales data including:
- Order Date
- Sales
- Profit
- Customer Name
- Segment
- Region
- Category & Sub-Category

---

## Data Preparation Steps
1. Imported CSV dataset into Power BI
2. Checked and corrected data types
3. Created calculated columns for:
   - Month Name
   - Month Number (for proper sorting)
4. Created DAX measures for KPIs

---

## Key DAX Measures

Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Total Orders = COUNT(Orders[Order ID])

---

## Dashboard Features
Filters (Slicers)

- Region

- Category

- Sub-Category

- Order Date (Between Date Range)

These slicers enable interactive, drill-down analysis.

---


## Visualizations Used
1. KPI Cards

- Total Sales

- Total Profit

- Total Orders

Purpose: Quick high-level performance snapshot.
2. Monthly Sales Trend

- Visual: Line Chart

- X-Axis: Order Date (Month)

- Y-Axis: Total Sales

Purpose: Identify seasonality and sales trends over time.

3. Sales by Category

- Visual: Bar Chart

- X-Axis: Category

- Y-Axis: Total Sales

Purpose: Compare revenue contribution across product categories.
4. Profit by Segment

- Visual: Donut Chart

- Legend: Segment

- Values: Total Profit

Purpose: Understand profitability across customer segments.

5. Top 10 Customers by Sales

- Visual: Bar Chart

- Filter: Top N → Top 10 by Total Sales

Purpose: Identify key customers driving revenue.

----


## Business Insights Enabled

- Detect high-performing regions and categories

- Identify seasonal sales patterns

- Focus marketing and retention efforts on top customers

- Compare profit contribution across customer segments

---

## How to Use the Dashboard

- Open the .pbix file in Power BI Desktop

- Use slicers to filter data dynamically

- Hover over visuals for detailed tooltips

- Combine filters to perform deeper analysis

---

## Project Outcome

This dashboard demonstrates:

- Strong understanding of business KPIs

- Effective use of DAX measures

- Clean dashboard design principles

- Ability to translate raw data into actionable insights

----

## Future Improvements

- Add YoY growth metrics

- Include profit margin analysis

- Create drill-through pages for customer-level analysis


---

## Author

Tehmina Afzal -AI & Data Science Intern at ITSOLERA Pvt. Ltd.
