# Global Retail Sales Performance Dashboard (2020–2024)

This analytical dashboard examines global retail sales performance between 2020 and 2024 using transactional and product-level data from a multinational retail dataset. The goal of the project is to understand revenue trends, customer demand patterns, and profitability while identifying performance gaps and opportunities for optimization.  

The project includes descriptive, diagnostic, and comparative analytics across regions, product categories, and customer segments. All data was cleaned, aggregated, and modeled in Power Query, with business logic and KPIs computed in DAX before visualization in Power BI.

---

## 🎯 Analytical Objectives

The analysis addresses four major performance categories:

1. **Revenue Growth & Time Trends**  
2. **Category-Level Demand & Profitability**  
3. **Regional Market Performance**  
4. **Customer Segment Behavior**

The dashboard highlights key patterns and provides insights and strategic recommendations for stakeholders responsible for sales strategy, product portfolio management, and pricing decisions.

---

## 📁 Dataset & Data Model

The final data model consisted of **five structured tables**, totaling **3.2 million records**:

| Table | Description |
|-------|-------------|
| Sales_Fact | Main transactional fact table including dates, products, customers, revenue, units, and margins |
| Date_Dim | Calendar table enabling year, quarter, and month hierarchies |
| Product_Dim | Product category, subcategory, cost, and pricing metadata |
| Region_Dim | Geographic attributes including country and sales market |
| Customer_Dim | Customer segmentation including loyalty status and channel |

### 🧮 Key Measures & KPIs

The following DAX measures powered the dashboard:

- **Total Revenue**
- **Gross Profit & Margin %**
- **Year-over-Year (YoY) Growth**
- **Units Sold**
- **Average Selling Price (ASP)**
- **Customer Retention & Repeat Rate**

---

## 📊 Executive Summary

### Overview of Findings

Between 2020 and 2024, global retail revenue grew consistently despite pandemic-related disruptions and supply chain complexities. Profitability remained volatile due to promotions, margin compression, and category mix shifts.

Key highlights:

- **Total revenue increased 34.6%** from 2020 to 2024.
- **Profit margin declined from 31.2% to 27.8%**, reflecting competitive pricing and discounting pressure.
- **Online channels grew 52%**, while physical retail grew 11%.
- **Customer repeat purchases increased 19%**, indicating improved retention.

---

## 🔍 Insights Deep Dive

### Category 1 — Revenue & Time Trends

Revenue accelerated post-2021, driven by e-commerce expansion:

- 2020 revenue: **$4.8B**
- 2024 revenue: **$6.46B**
- YoY growth peaked at **14% in 2022**

#### Visualization
![PHS.png)

---

### Category 2 — Category-Level Demand & Profitability

Product category analysis revealed:

- **Electronics** generated the highest revenue share (33%) but suffered margin declines due to heavy discounting.  
- **Home & Lifestyle** had the strongest profitability (38% margin) and stable demand patterns.  
- **Grocery** delivered volume but limited profit contribution due to slim margins.  

#### Visualization
![Category Comparison](PHS.png)

---

### Category 3 — Regional Market Performance

Regional analysis showed:

- **North America** remained the strongest revenue driver (42% share)  
- **Asia-Pacific** recorded the fastest growth rate at **21% CAGR**  
- **Europe** experienced margin pressure due to logistics and cost inflation  

#### Visualization
![Regional Performance Map](PHS.png)

---

### Category 4 — Customer Segment Behavior

Customer segmentation revealed evolving purchasing behaviors:

- **Loyalty members generated 54% of total revenue**  
- **Subscription customers** had 2.3× higher repeat rate than non-members  
- **Online-only shoppers** preferred higher-margin products compared to in-store buyers  

#### Visualization
![Customer Segments](PHS.png)

---

## 🧰 Tools & Methods Used

- **Power BI** (visualization & modeling)  
- **Power Query** (ETL & data preparation)  
- **DAX** (KPI & measure calculations)  
- **Excel / CSV** (data sources)  
- **Python (optional)** for exploratory data analysis

---

## 🚀 Live Dashboard Link

Power BI Dashboard: [View Live Dashboard](https://app.powerbi.com/view?r=EXAMPLE_DUMMY_LINK)

---

## 📦 Repository Structure



