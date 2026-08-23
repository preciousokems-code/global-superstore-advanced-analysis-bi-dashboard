# Global Superstore Advanced Analytics Dashboard

Advanced data analysis and interactive Power BI dashboard built on the Global Superstore dataset — covering sales, profitability, product, geographic, customer, and discount performance, backed by DAX measures and evidence-based business recommendations.

**Programme:** AnalystLab Africa — Data Analytics Internship, Week 3
**Tools:** Microsoft Power BI · Power Query · DAX · Excel

---

## 📌 Project Overview

This project builds on a Week 2 exploratory analysis of the Global Superstore dataset. In Week 3, the analysis was extended into a full business intelligence solution: deeper analysis of sales and profitability drivers, six-plus KPIs, ten DAX measures, and a three-page interactive Power BI dashboard designed for a business stakeholder audience.

The goal was to answer a set of core business questions:
- What is driving sales performance?
- What is affecting profitability?
- Which products or categories are underperforming?
- Which regions or markets offer growth opportunities?
- Are discounts affecting profitability?
- Which customer segments are most valuable?

## 🗂️ Dataset

**Global Superstore Dataset** — order-level retail transaction data including Sales, Profit, Discount, Shipping Cost, Category/Sub-Category, Customer Segment, and Region/Market/Country geography.

## 📊 Dashboard Pages

| Page | Focus |
|---|---|
| **1. Executive Performance Overview** | KPI summary, yearly/quarterly/monthly sales & profit trends, profit by category and sub-category |
| **2. Product & Geographic Performance** | Top profitable & loss-making products, sales/profit by market, regional performance, map view |
| **3. Customer & Discount Insights** | Sales/profit by segment, top customers by sales vs. profit, discount vs. sales/profit, category-level discount and shipping cost breakdown |

![Global Superstore Dashboard Preview](Global_Superstore_Dashboard_LinkedIn_Landscape.png)

## 🧮 Key KPIs

- Total Sales: **$12.64M**
- Total Profit: **$1M**
- Profit Margin: **11.61%**
- Total Orders: **25K**
- Total Customers: **795**
- Average Sales per Order: **$246.49**

## ➗ DAX Measures

Ten calculated measures power the dashboard, including `Total Sales`, `Total Profit`, `Profit Margin`, `Average Sales per Order`, `Average Profit per Order`, `Average Discount`, `Loss-Making Orders`, and year-over-year `Sales Growth %` / `Profit Growth %`. Full formulas and purpose notes are documented in [`DAX_Measures_Documentation.docx`](./DAX_Measures_Documentation.docx).

## 💡 Key Business Insights

1. **Consumer, Central, and APAC drive sales** — Consumer generates ~51.5% of total sales; Central is the top region (~$2.82M); APAC is the top market (~$3.59M).
2. **Furniture is the weakest category by profit** — highest average discount (17%) *and* highest shipping cost, pointing to a combined discount + logistics cost problem rather than discounting alone.
3. **Several high-sales products post losses** — e.g. Motorola Smart Phone ($38.9K sales, -$4.4K profit), Rogers Lockers, HowVwer Stove White.
4. **Africa and Canada underperform** — lowest regional sales/profit (Africa, ~$783K) and lowest market sales/profit (Canada, ~$67K) versus Central/APAC.
5. **Discount impact on profit is mixed**, not linear — larger discounts don't consistently improve sales or profit.
6. **Profit leadership ≠ sales leadership** — Tom Ashbrook is the top customer by sales, but Tamara Chand is the top customer by profit.

Full analysis and recommendations are documented in [`Business_Insights_and_Recommendations.docx`](./Business_Insights_and_Recommendations.docx).

## 📁 Repository Structure

```
├── README.md
├── Global_Superstore_Advanced_Data_Analysis.docx
├── Global_Superstore_Business_Insights_and_Recommendations.docx
├── Global_Superstore_DAX_Measures_Documentation.docx
├── Global_Superstore_Dashboard_LinkedIn_Landscape.png
├── dashboard/
│   └── Global_Superstore_Dashboard.pbix
└── screenshots/
    ├── 01_executive_overview.png
    ├── 02_product_geographic.png
    └── 03_customer_discount.png
```

## 📄 Deliverables

- [x] Power BI Dashboard (.pbix)
- [x] Dashboard screenshots / PDF export
- [x] Advanced Data Analysis document
- [x] Business Insights & Recommendations report
- [x] DAX Measures documentation
- [x] README.md

## 👤 About

Built as part of the **AnalystLab Africa Data Analytics Internship Programme**, Week 3: Advanced Data Analysis, KPI Development & Business Intelligence Dashboard.

`#AnalystLabAfrica` `#DataAnalytics` `#PowerBI`
