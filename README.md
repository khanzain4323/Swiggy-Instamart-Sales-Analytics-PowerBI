## Swiggy Instamart Sales Analytics Dashboard

An interactive **Power BI** dashboard analyzing sales performance, order distribution, shop sizes, and product category trends for Swiggy Instamart.
---

## Live Interactive Dashboard

Explore the live, interactive Power BI report directly in your browser:

**[Launch Live Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZTBkMDY4YjktYzk1Ny00NjY5LWJiZWYtZDlhMDI0MTBlZjQzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

<iframe width="100%" height="600" src="https://app.powerbi.com/view?r=eyJrIjoiZTBkMDY4YjktYzk1Ny00NjY5LWJiZWYtZDlhMDI0MTBlZjQzIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9" frameborder="0" allowFullScreen="true"></iframe>

> **Note:** If the embedded view above does not render in your environment, please use the direct link above to open the report in a new tab.
---

## Dashboard Overview

![Swiggy Instamart Dashboard Overview](assets/dashboard_overview.png)
---
## Business Key Performance Indicators (KPIs)

| KPI Metric | Value |
| :--- | :--- |
| **Total Sales** | **$1.20M** ($1,201,811.49) |
| **Total Orders** | **8.52K** (8,523 orders) |
| **Average Customer Rating** | **3.92 / 5.0** |
| **Average Sales / Order** | **$141.01** |
| **Average Item Weight** | **12.86** |
---
## Key Insights & Findings
* **Top Product Categories:** **Fruits & Vegetables** ($178.15K) and **Snack Foods** ($175.43K) are the primary revenue drivers, followed closely by Household items ($135.98K).
* **City Tier Performance:** **Tier 3 cities** generated the highest sales volume (**$472.21K / 39.29%**), leading Tier 2 ($393.15K / 32.71%) and Tier 1 ($336.45K / 28.00%).
* **Outlet Analysis:** **Supermarket Type 1** dominates outlet sales, generating **$787,669.89** across 5,577 total orders (over 65% of overall sales volume).
* **Outlet Ratings:** **Grocery Stores** maintain the highest average rating at **3.93**, with Supermarket Type 1 and Type 2 averaging **3.92**.
---
## Tech Stack & Features
* **Business Intelligence:** Power BI Desktop
* **Data Transformation:** Power Query
* **Interactive Slicers:** Dynamic filtering by **Year** (2021–2024), **Shop Size** (High, Medium, Small), and **City Tier** (Tier 1, Tier 2, Tier 3).
* **Visualisations:** Custom Funnel Chart (Categories), Donut Charts (City Tier Distribution & Outlet Sizes), Stacked Bar Charts, Line Chart (Opening Year Sales Trend).
---
## Repository Structure
```text
Swiggy-Instamart-Sales-Analytics-PowerBI/
├── assets/
│   ├── dashboard_overview.png
│   ├── filter_panel_view.png
│   └── category_breakdown.png
├── data/
│   └── swiggy_instamart_data.csv
├── pbix/
│   └── Swiggy_Instamart_Analytics.pbix
└── README.md

## Author
Zainul Abedeen

## License
This project is licensed under the MIT Lincense. 
