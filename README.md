# E-commerce Sales Dashboard — IEEE Hackathon 2023

>  Built for **IEEE Hackathon 2023** — Interactive sales intelligence dashboard analyzing e-commerce performance across regions, categories, and time periods using Microsoft Excel

---

## Dashboard Preview

![Dashboard](dashboard%20.png)

---

## Overview

An interactive Excel dashboard built to analyze e-commerce business performance across sales, profit, and return metrics. The dashboard enables business stakeholders to explore trends by region, product category, ship mode, and time period — all through dynamic slicers and pivot-driven visualizations.

---

## Hackathon Context

| Detail | Info |
|--------|------|
| Event | IEEE Hackathon 2023 |
| Challenge | Build a data-driven business intelligence solution |
| Tool Used | Microsoft Excel (Pivot Tables, Charts, Slicers) |
| Deliverables | Interactive dashboard + full analysis report |
| Full Report | `Report.pdf` |

---

## Dataset

 **File:** `Data.xlsx`

The dataset contains global e-commerce transaction records with the following key fields:

| Field | Description |
|-------|-------------|
| Order Date | Date of the transaction |
| Ship Mode | Shipping method (Standard, Second Class, First Class, Same Day) |
| Region | Geographic region of the order |
| Country / City | Country and city of the customer |
| Category | Product category (Technology, Furniture, Office Supplies, Fashion) |
| Sales | Revenue generated from the order |
| Profit | Profit earned from the order |
| Returns | Whether the order was returned |

---

## KPIs Tracked

| KPI | Description |
|-----|-------------|
| Total Sales | Aggregate revenue across all orders |
| Total Profit | Net profit across all regions and categories |
| Monthly Sales Trend | Month-over-month revenue performance |
| Monthly Profit Trend | Month-over-month profit performance |
| Sales by Country | Top contributing countries by revenue |
| Profit by Country | Top contributing countries by profit |
| Returns by Category | Return volume breakdown by product category |
| Returns by City | Cities with highest return volumes |

---

## Key Findings

**Sales**
- The **United States** contributes the highest share of total sales across all regions
- Monthly sales show consistent performance with peak volumes in specific months of the year
- Sales trends vary significantly across ship modes — Standard Class dominates volume

**Profit**
- Highest profits generated from the **United States**, followed by Australia, France, Mexico, and Germany
- Profit margins differ by product category — Technology tends to yield the highest margins

**Returns**
- **Fashion** category records the highest number of returns across all categories
- Cities with the highest return volumes include **New York**, **Los Angeles**, and **San Francisco**
- Return patterns suggest potential quality or expectation-mismatch issues in specific categories

---

## Dashboard Features

**Interactive Slicers**
- Ship Mode (Standard Class, Second Class, First Class, Same Day)
- Region (Central, East, West, South)
- Product Category (Technology, Furniture, Office Supplies, Fashion)

**Visualizations**
- Monthly Sales Trend (line chart)
- Monthly Profit Trend (line chart)
- Sales by Country (bar chart)
- Profit by Country (bar chart)
- Returns by Category (bar chart)
- Returns by City (bar chart)

**Excel Techniques Used**
- Pivot Tables for dynamic data aggregation
- Pivot Charts linked to slicers for interactive filtering
- Conditional formatting for KPI highlighting
- Named ranges for clean formula referencing

---

## Project Structure

```
├── Data.xlsx          # Source dataset — e-commerce transaction records
├── dashboard .png     # Dashboard screenshot preview
├── Report.pdf         # Full analysis report (IEEE Hackathon submission)
└── README.md          # Project documentation
```

> 📝 **Note:** Rename `dashboard .png` → `dashboard.png` (remove the space) for consistent image rendering across all platforms.

---

## How to Open

```
1. Download Data.xlsx
2. Open in Microsoft Excel (2016 or later recommended)
3. Enable editing if prompted
4. Use the slicers on the dashboard sheet to filter by:
   - Ship Mode
   - Region
   - Product Category
5. View Report.pdf for the full written analysis
```

---

## Applications

- E-commerce sales performance monitoring
- Regional and category-level profitability analysis
- Return rate analysis and reduction strategy
- Executive dashboard reporting and stakeholder communication
- Business intelligence for inventory and marketing decisions

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Dashboard, Pivot Tables, Charts, Slicers |
| Pivot Tables | Dynamic data aggregation and summarization |
| Pivot Charts | Interactive visualizations linked to slicers |
| Conditional Formatting | KPI highlighting and data callouts |

---

## Author
Ramu Battu

**Ramu Battu**
MS in Data Analytics — California State University, Fresno
📧 ramuusa61@gmail.com
