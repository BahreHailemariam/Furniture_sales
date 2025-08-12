# Furniture Sales Analysis & Dashboard in Excel
Excel-based solution for loading, transforming, analyzing, and visualizing furniture sales data—complete with interactive dashboards and pivot-based insights.
## Project Overview
A full-cycle Excel project from raw data to impactful dashboard. Designed to empower stakeholders with meaningful insights through data cleaning, transformation, pivot analysis, and visualization.
## Project Scope & Objectives
- **Data Loading & Transformation:** Import dataset, clean it using Power Query or manual steps, and prepare it for analysis.

- **Analytical Modeling:** Leverage PivotTables and formulas (**SUMIFS**, **VLOOKUP**, **IFERROR**, **INDEX/MATCH**) for slicing data by time, region, product, and more.

- **Visualization & Dashboarding:** Build interactive dashboards with pivot charts, slicers, and summary KPIs.

- **Reports & Pivot Pivoting:** Enable dynamic exploration via pivot layouts tailored to categories, branches, and years.

- **Key Questions Addressed:** Trends over time, best products/regions, revenue vs. units, manager comparisons—tailored to support strategic decisions.
## Tools & Techniques Used
- Microsoft Excel (2016+)

- Power Query (for ETL automation)

- PivotTables & PivotCharts

- Excel Formulas: **SUMIFS**, **VLOOKUP**, **IFERROR**, **INDEX/MATCH**

- Interactive Features: Slicers, conditional formatting, linked visuals
## Typical Workflow & Features
**1. Data Loading & Transformation**

   - Import data into Excel or Power Query.

   - Clean and format fields: dates, categories, numeric conversions.

**2. Pivot Analysis**

   - Build PivotTables: e.g., sales by region, product category, month/year.

   - Compute metrics like total revenue, units sold, profitability.

**3. Dashboard Visualization**

   - Design PivotCharts (line, bar, area, map).

   - Add slicers for dynamic filtering by time, region, category.

   - Showcase key metrics visually, following best layout practices (clear labeling, intuitive grouping).

**4. Interactivity & Insights**

   - Enable interactive exploration with slicers and linked visuals.

   - Highlight trends (e.g. seasonal spikes, product hotspots).

   - Present top-selling products, high-performing regions, and other actionable insights.

## Project Structure
``` bash
Furniture-Sales-Analysis-Excel/
├── data/
│   └── furniture_sales_raw.xlsx     # Original raw dataset
├── analysis/
│   └── transformed_data.xlsx        # clean and structured dataset
├── dashboard/
│   └── Furniture_Sales_Dashboard.xlsx # Interactive Excel dashboard
├── assets/
│   └── dashboard_screenshot.png     # Visual preview of the dashboard  and Visual snapshot of the dashboard
├── README.md
└── requirements.txt                 # Excel version and notes
```
## Example Real-World Dashboards
- Furniture-Sales-Analysis-Project by Bahre shows effective use of pivots, formulas, and dashboards for performance comparisons across regions, products, and managers.
GitHub

- Furniture-sales-and-revenue-analysis by Bahre showcases KPIs like total revenue, profit margins, and product/region performance—perfect for inspiration.
## Quick Start Guide
1. Clone the repository:
```bash

git clone <repo-url>
cd Furniture-Sales-Analysis-Excel/
```
2. Place the sales dataset file (`furniture_sales_raw.xlsx`) in the `data/` folder.

3. Open Excel:

  - Load & Clean data using Power Query or manual extraction into a clean Data tab.

  - Create PivotTables to summarize data (by year, category, region, manager, etc.).

  - Build Visuals with PivotCharts, slicers, and KPI metrics.

4. Save your work in the `dashboard/` folder as an interactive `.xlsx`.
## Dashboard Features
- **Summary Metrics:** Total sales, total revenue, profit margin, number of orders.

- **Pivot-Based Analysis:**

   - Sales by Region, Product Category, Year

   - Branch Manager performance comparisons

   - Time-series trends and annual growth

- **Interactive Elements:**

   - Slicers for filtering by region, product, year, etc.

   - Dynamic pivot charts and linked visuals

   - Conditional formatting for highlighting insights
## Dashboard Design Best Practices
- Group related metrics for clarity—e.g., top-level KPIs, followed by detailed breakdowns.

- Use consistent color schemes, avoid clutter, and maintain clean labeling and layout.
## Future Enhancements
- Automate **ETL** with Power Query and connected data models.

- Integrate Power Pivot for **DAX**-driven advanced calculations.

- Add forecasting or trend projections using built-in Excel features.

- Explore geographic or visual enhancements like maps or heatmaps.
## License & Contributions
- **License: MIT** (feel free to adjust as necessary)

- **Contributions:** Pull requests and feedback welcomed—whether it’s enhanced visuals, formula optimizations, or new analysis perspectives!
