# Power BI Portfolio — Varun Kapse

Three interactive Power BI dashboards built from a ~10,000-row retail dataset,
covering sales analysis, operational performance, and data quality. Each dashboard
uses custom DAX measures, interactive slicers, and multiple linked visuals.

---

## 1. Retail Sales Dashboard

![Retail Sales Dashboard](retail-sales-dashboard.png)

An interactive overview of sales performance across regions, categories and products.

- **KPIs:** Total Sales (£2.3M), Total Profit, Profit Margin, Order Quantity
- **Custom DAX measure:** Profit Margin = profit ÷ sales
- **Visuals:** sales by region, by category, and by sub-category
- **Interactivity:** slicers for Region and Segment filter the whole page
- **Insight:** Technology and the West region drive the largest share of sales; a small number of sub-categories account for most revenue.

---

## 2. Operational Performance Dashboard

![Operational Performance Dashboard](operational-performance-dashboard.png)

A view of how the business delivers — shipping, volume, and discounting.

- **KPIs:** Order Quantity, Sales, Profit, Average Discount (15.6%)
- **Visuals:** quantity by ship mode, quantity by region, and a discount-vs-profit scatter across sub-categories
- **Insight:** the scatter reveals sub-categories where high discounts coincide with low or negative profit — a clear signal of where discounting is eroding margin.

---

## 3. Data Quality & Integrity Dashboard

![Data Quality Dashboard](data-quality-integrity.png)

A data-governance view auditing completeness and flagging problem records.

- **Custom DAX measures:** Total Records, Missing Postal Codes, Postal Code Completeness, Loss-Making Orders, % Loss-Making
- **Findings:** 100% postal-code completeness; **18.7% of all orders are loss-making**, concentrated in specific sub-categories
- **Why it matters:** surfacing data completeness and unprofitable transactions is a core part of data quality and governance work.

---

## Tools & Skills
Power BI Desktop · DAX · data modelling · KPI design · interactive dashboards · data quality analysis

## Data
Sample Superstore dataset (~10,000 rows of retail orders). 
