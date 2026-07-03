# Online Retail Sales Analysis – Excel Portfolio Project

## Project Title
**Online Retail Sales Performance Dashboard & Insights**

---

## Project Overview
This project is a complete data analytics workflow built entirely in **Microsoft Excel**. It uses a publicly available online retail dataset to clean, transform, analyze, and visualize sales performance. The final output includes an interactive dashboard with slicers and timelines, alongside a business insights report.

The goal is to demonstrate practical Excel skills—from raw data to business-ready reporting—in a clear and professional manner for recruiters and portfolio viewers.

---

## Business Objective
The primary business objective is to:
- Understand overall sales performance (revenue, order volume, customer trends).
- Identify top-performing products, countries, and time periods.
- Highlight key sales patterns to support inventory, marketing, and international expansion decisions.
- Present findings in an accessible, interactive format for stakeholders.

---

## Dataset Description
- **Source**: Online retail transaction data (publicly available UCI Machine Learning Repository-style dataset).
- **Scope**: Transactions from a UK-based online retailer between **December 1, 2010 – December 9, 2011**.
- **Key Columns**:
  - InvoiceNo
  - StockCode
  - Description
  - Quantity
  - InvoiceDate
  - UnitPrice
  - CustomerID
  - Country

> **Note**: The dataset ends on December 9, 2011. Therefore, December 2011 data is **incomplete** and any month-over-month drop involving December should be interpreted with caution.

---

## Tools Used
- **Microsoft Excel** (Version compatible with Power Query, PivotTables, and PivotCharts)
- **Power Query** – for data cleaning and transformation
- **PivotTables & PivotCharts** – for aggregation and visualization
- **Slicers & Timeline** – for interactive filtering
- **Dashboard Design** – for executive summary view

No external tools or coding languages (Python, SQL, etc.) were used in this project.

---

## Workbook Structure
The Excel workbook is organized into the following sheets:

| Sheet Name | Description |
|------------|-------------|
| **Online Retail Raw Data** | Original unmodified dataset |
| **Clean Sales Data** | Data after cleaning (removed nulls, negative quantities, invalid prices) |
| **Customer Sales Data** | Aggregated customer-level metrics |
| **Sales by Country** | Country-wise revenue and transaction counts |
| **Invoice Summary** | Summary per invoice (total amount, line items) |
| **Pivots** | Central sheet containing all PivotTables used for analysis |
| **Dashboard** | Final interactive dashboard with charts, slicers, and timeline |
| **Insights and Trends** | Written business insights derived from the analysis |

---

## Dashboard Features
The interactive dashboard includes:
- **Key Performance Indicators (KPIs)**:
  - Total Revenue: **$10.6M**
  - Total Invoices: **19,960**
  - Average Invoice Value: **$533.17**
  - Countries Served: **38**
- **Charts**:
  - Monthly Revenue Trend
  - Sales by Country (Top 10)
  - Top Products by Revenue
  - Domestic vs. International Sales Split
- **Interactivity**:
  - **Slicers** for Country, Product Category (where applicable)
  - **Timeline** filter for Invoice Date range

---

## Key Insights
1. **Total Revenue**: The business generated **$10.6M** during the analysis period.
2. **Invoice Volume**: There were **19,960** total invoices, with an average value of **$533.17**.
3. **Geographic Concentration**:
   - **Domestic (UK) sales account for 90%** of total revenue.
   - International sales contribute the remaining **10%**, spread across **38 countries**.
4. **Seasonality**:
   - Peak sales months are **September to November**.
   - December 2011 appears lower but is **incomplete** in the dataset.
5. **Product Concentration**:
   - Three products contribute **47%** of total revenue:
     - DOTCOM POSTAGE
     - REGENCY CAKESTAND 3 TIER
     - PAPER CRAFT , LITTLE BIRDIE

---

## Business Recommendations
1. **Explore International Expansion**  
   With 90% of sales from the UK, there is potential to grow in existing international markets or target new ones.

2. **Leverage Peak Season**  
   Plan marketing campaigns, promotions, and inventory buildup ahead of the **September–November** peak period.

3. **Review Product Dependency**  
   Since three products account for nearly half of revenue, consider diversifying the product mix or bundling strategies to reduce risk.

4. **Investigate December Drop Cautiously**  
   Avoid overreacting to December’s decline—it is likely due to incomplete data. Full-year 2011 data would provide clearer seasonality signals.

---

## Skills Demonstrated
- **Data Cleaning** using Power Query (removing nulls, duplicates, outliers).
- **Data Modeling** with calculated columns and measures.
- **PivotTable & PivotChart** creation for multidimensional analysis.
- **Dashboard Design** with layout, formatting, and UX considerations.
- **Interactivity** using slicers and timeline controls.
- **Business Storytelling** – translating numbers into actionable insights.

---

## Conclusion
This project showcases a complete end-to-end data analysis workflow in Excel. It demonstrates how to turn raw transactional data into a professional, interactive dashboard with clear business insights—all without leaving the spreadsheet environment. It is a strong addition to any data analytics portfolio, especially for roles requiring advanced Excel proficiency.

---

## How to Use This Repository
1. Download the Excel file from this repository.
2. Open the file in Microsoft Excel (desktop version recommended).
3. Navigate to the **Dashboard** sheet to explore the visuals.
4. Use the **slicers** and **timeline** to filter by country, date, or other dimensions.
5. Review the **Insights and Trends** sheet for a written summary.

---

*Project completed as part of a data analytics portfolio. All work done in Microsoft Excel without external scripting or coding tools.*
