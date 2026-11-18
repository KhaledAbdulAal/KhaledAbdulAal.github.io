# 📊 EG-SALES: 2025 E-commerce Sales & Profitability Analysis

## 📌 Project Overview
**EG-SALES** is an end-to-end data analysis project built in **Microsoft Excel** that evaluates the 2025 sales performance of a simulated Egyptian e-commerce company (~6,000 orders). The synthetic dataset is modeled after real-world Egyptian market dynamics—incorporating local seasonality (Ramadan, White Friday), regional distribution across Egyptian governorates, and local payment behaviors.

### 🎯 Business Problem
> *"Sales are growing, but profit doesn't seem to be growing at the same rate. Where are we winning, and where are we losing?"*

Framed as an executive request from the Sales Manager ahead of next year's promotional budget allocation, this project identifies key profit drivers, margin leaks, regional bottlenecks, and discount efficiencies.

---

## 🛠️ Tools & Methodology
* **Data Cleaning & Preparation:** Identified and resolved **17 distinct data quality issues**, including duplicate records, inconsistent text formatting, missing customer/payment attributes, invalid quantities/prices, date anomalies, and statistical outliers using lookup-based validation.
* **Data Modeling & Analysis:** Engineered calculated metrics (Net Revenue, Gross Profit, Profit Margin %, AOV) using advanced Excel formulas.
* **Interactive Dashboarding:** Built a dynamic executive dashboard powered by **PivotTables**, **PivotCharts**, **Slicers**, and an interactive **Date Timeline** for multi-dimensional filtering.

---

## 📈 Headline KPIs (2025 Performance)
| Metric | Value | Notes |
| :--- | :--- | :--- |
| **Net Revenue** | **4,966,382 EGP** | Calculated on *Delivered* orders only |
| **Gross Profit** | **1,450,327 EGP** | ~29.20 EGP retained per 100 EGP in revenue |
| **Overall Profit Margin** | **29.20%** | Baseline profitability benchmark |
| **Average Order Value (AOV)** | **988 EGP** | Delivered orders average |
| **Shipping Fee Contribution** | **4.97%** | Customer-paid shipping share of revenue |
| **Returned Rate** | **7.70%** | Calculated across all placed orders |
| **Cancelled Rate** | **8.50%** | Calculated across all placed orders |
| **Returning Customer Rate** | **92.68%*** | *See Limitations & Assumptions below* |

---

## 🔍 Key Findings
1. **Seasonality vs. Target Attainment:** Sales experienced a noticeable uplift during **Ramadan** and a major surge during **White Friday (November)**. However, monthly revenue targets were only met in **3 out of 12 months** (February, May, and June).
2. **Product Margin Inverse Relationship:** Lower-revenue items (e.g., *Body Lotion*, *Tea Pack*, *Face Wash*) consistently generated higher profit margins (**42%–44%**), whereas top revenue drivers like *Smartphone A-S* and *Handbag* yielded significantly thinner margins (**19.7%–21.8%**).
3. **Geographic & Category Return Hotspots:** 
   * **Upper Egypt** recorded the highest combined return and cancellation rates: **Assiut (23.53%)**, **Beni Suef (20.44%)**, and **Minya (20.31%)**.
   * **Fashion** suffered from a disproportionately high return/cancellation rate (**24.98%**) compared to other categories like *Grocery & Household* (**10.74%**).
   * Rates remained uniform across sales channels, indicating product/regional fulfillment issues rather than channel friction.
4. **Market Concentration:** **Cairo** is the primary market leader (**1,277 orders**), followed by **Giza (767)** and **Alexandria (565)**.
5. **Discount Diminishing Returns:** Higher discount tiers directly eroded profit margins without driving proportional increases in order quantities—except during **White Friday**, where volume rose across all discount levels.

---

## 💡 Strategic Recommendations
1. **Cap Deep Discounting & Shift to Targeted Promotions:** Avoid blanket discount increases outside major peak events. Maintain moderate discount tiers and reallocate promotional budgets toward high-margin, lower-revenue products to protect and expand the **29.20%** overall margin.
2. **Audit High-Risk Regions & Fashion Fulfillment:** Investigate operational, courier, and sizing/quality issues driving the high return/cancellation rates in **Assiut, Beni Suef, and Minya**, specifically within the **Fashion** category.
3. **Optimize Peak-Season Campaigns:** Capitalize on organic traffic surges during **Ramadan** and **White Friday** by bundling high-margin accessories and personal care items with flagship electronics.

---

## ⚠️ Limitations & Assumptions
* **Synthetic Dataset:** While patterns reflect realistic Egyptian e-commerce behavior, figures are simulated and do not represent an actual business.
* **Repeat Customer Rate (92.68%):** Inflated due to a constrained simulated pool of 2,000 unique customers across ~6,000 orders rather than true organic retention.
* **Shipping Economics:** Only customer-paid shipping fees were recorded; actual carrier costs were unavailable, making shipping profitability directional.
* **Calculation Basis:** Revenue, Gross Profit, and AOV are strictly based on **Delivered** orders, whereas Cancellation and Return rates reflect **Total Orders**.

---

## 📂 Repository Structure
```text
├── EG-SALES_2025_Analysis.xlsx      # Raw data, 17-step cleaning log, PivotTables & Interactive Dashboard
├── Ecommerce_Sales_2025_Report_EN.pdf # Executive presentation & visual insights report
└── README.md                          # Project documentation
```