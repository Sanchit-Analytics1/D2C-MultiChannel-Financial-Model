# Multi-Channel D2C Financial Model & Executive Dashboard

A dynamic, three-tier financial model built in Excel for analyzing multi-channel D2C revenue performance, automated P&L budget-variance tracking, and executive KPI reporting.

---

## 📌 Project Overview
This project models financial performance across three primary distribution channels: **Shopify**, **Marketplace**, and **Retail Store**. It converts raw transactional data into dynamic P&L insights and executive visual analytics.

## 🏗️ Model Architecture
* **`Sales_Data`**: Transactional data engine tracking revenue streams, discounts, COGS, and channel attribution.
* **`Channel_Summary`**: Dynamic Pivot aggregation layer summarizing Gross Revenue, Net Sales, and Contribution Margin.
* **`Budget_Variance`**: Automated MIS variance control tracking Budget vs. Actual performance ($ variance and % variance) using `GETPIVOTDATA` and `SUMIF`.
* **`Management_Dashboard`**: C-suite presentation layout featuring dynamic KPI callouts and visual charts (Clustered Column & Doughnut charts).

---

## 📊 Key Highlights & Metrics
* **Total Net Sales**: ₹10,23,500 across all channels.
* **Total Contribution Margin**: ₹3,37,896.
* **Shopify Performance**: Led net sales growth (+14% over budget) and generated the highest contribution margin (₹1,41,885).
* **Cost Variance Insight**: Identified a -73% unfavorable COGS variance in Marketplace sales, pointing to high channel logistics/commission expenses.

---

## 🛠️ Excel Functions & Techniques Applied
* Dynamic Lookup & Data Pipelines (`GETPIVOTDATA`, `SUMIF`, `SUM`)
* Pivot Tables & Automated Aggregations
* Variance Analysis & Financial Modeling logic
* Executive Dashboarding & Visual Data Formatting
