# Superstore Executive Sales & Discount Leakage Analysis

An interactive two-page **Tableau** dashboard (`1200x900`) built to evaluate revenue growth, regional profitability, and margin erosion caused by discounting across segments, shipping modes, and product sub-categories.

## Live Dashboard & Previews

[![Tableau Public](https://img.shields.io/badge/Tableau%20Public-View%20Live-E97627?logo=tableau&logoColor=white)](https://public.tableau.com/app/profile/meenakshi.singh1303/viz/Superstore_Executive_Sales_Analysis/ExecutiveOverviewFinancialHealth)


### Page 1: Executive Overview & Financial Health
<details>
<summary>🔍 Click here to view Executive Overview & Financial Health</summary>

![Page 1: Executive Overview & Financial Health](images/images/1_Executive_Overview.png)

</details>

### Page 2: Discount Leakage & Deep-Dive Analysis
<details>
<summary>🔍 Click here to view Discount Leakage & Deep-Dive Analysis</summary>

![Page 2: Discount Leakage & Deep-Dive Analysis](images/images/2_Deep-Dive_Analysis.png)

</details>

## Key Dashboard Highlights
- **Executive Overview & Financial Health:** Tracks headline KPIs (**Total Sales**, **Total Profit**, **Overall Profit Margin %**, **Total Orders**) alongside a regional profit/sales map, **Monthly Sales Trend** (Sales bars + Profit line with abbreviated month labels), **Top 10 Products by Sales**, and a **Category / Sub-Category** breakdown.
- **Discount Leakage & Deep-Dive Analysis:** Highlights discounting impact via **Average Discount Rate**, **Total Loss from Heavy Discount**, **Loss Making Orders %**, and **Average Shipping Days**, paired with **Profitability by Discount Tier**, **Sub-Category Profit Loss Ranking**, a **Customer Segment & Shipping Mode Matrix**, and a **Discount % vs. Profit Correlation Scatter Plot**.
- **Interactive Controls & UX:** Includes a collapsible left filter drawer (`Year`, `Region`, `Segment` on Page 1; `Year`, `Sub Category`, `Ship Mode`, `Discount Tier` on Page 2), custom tooltips across visuals, and smooth page navigation buttons.

## Dataset & Preparation
- **Source:** Superstore sales dataset (`clean_superstore.csv`), filtered and analyzed dynamically by year (e.g., `2017` view) and dimensional slices.
- **Calculated Metrics:** Profit margin ratios, discount tiers, heavy-discount loss tracking, loss-making order share, and shipping turnaround metrics.

## Repository Structure
- `tableau/` — Tableau workbook file
- `images/` — High-resolution dashboard screenshots for documentation
- `data/` — Cleaned dataset used for the analysis
