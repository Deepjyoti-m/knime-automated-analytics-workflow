# 📊 Automated Analytics Workflow (KNIME)

## 📌 Business Context
Manual data processing is time consuming and error prone. This project 
demonstrates how to build an automated ETL and analytics pipeline using 
KNIME, processing real retail transaction data and delivering category 
level KPIs automatically — reducing manual effort and enabling faster 
business decisions.

---

## 🎯 Project Objectives
- Build an automated ETL pipeline in KNIME
- Clean and transform raw retail transaction data
- Calculate unit price from sales amount and quantity
- Aggregate KPIs by product category automatically
- Complement KNIME workflow with Python analysis and visualizations

---

## 📊 Dataset Overview
- **Source:** Retail Sales Transaction Dataset (Kaggle)
- **Size:** 64,682 transactions
- **Key Fields:** Transaction ID, Customer ID, SKU Category, 
SKU, Quantity, Sales Amount, Date

---

## 📈 Financial Summary

| Metric | Value |
|--------|-------|
| Total Revenue | $1,578,038.62 |
| Total Transactions | 64,682 |
| Total Units Sold | 195,624 |
| Average Unit Price | $9.69 |
| Average Order Value | $24.40 |
| Total Product Categories | 187 |
| Top Category Revenue | $114,061.33 |

---

## 🔁 KNIME Workflow

### ETL Pipeline Structure
```
CSV Reader → Raw retail transaction data
      ↓
Math Formula → Calculate Unit Price (Sales Amount / Quantity)
      ↓
GroupBy → Aggregate KPIs by SKU Category
      ↓
CSV Writer → Export processed KPIs
```

### Workflow Nodes Used
- **CSV Reader** — Load raw transaction data
- **Math Formula** — Derive unit price metric
- **GroupBy** — Aggregate revenue, units and transactions by category
- **CSV Writer** — Export automated KPI output

---

## 🐍 Python Analysis

### Analysis Performed
- Revenue by product category
- Units sold by category
- Average unit price by category
- Transaction count by category
- Category performance summary

---

## 🔍 Key Insights

### 💰 Revenue Performance
- Total revenue of **$1.58M** across **64,682 transactions**
- Average order value of **$24.40** indicates high frequency low ticket purchases
- **187 product categories** show highly diversified product mix

### 📦 Product Analysis
- Top category generates **$114,061** in revenue
- Average unit price of **$9.69** confirms mass market positioning
- High transaction volume suggests strong repeat purchase behavior

### ⚙️ Automation Impact
- KNIME workflow processes **64,682 rows** automatically
- Unit price derivation applied consistently across all records
- Category KPI aggregation completed in seconds vs manual hours

---

## 💡 Business Recommendations
- **Focus on top categories** — concentrate marketing on highest revenue segments
- **Review low performing categories** — 187 categories need rationalization
- **Increase average order value** — current $24.40 has significant upsell potential
- **Automate monthly reporting** — extend KNIME workflow for scheduled KPI refresh
- **Bundle products** — combine low ticket items to increase transaction value

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| KNIME | ETL pipeline and workflow automation |
| Python | Category analysis and visualization |
| pandas & matplotlib | Data manipulation and charting |

---

## 📂 Repository Structure
```
knime-automated-analytics-workflow/
│
├── data/
│   ├── raw/                      # Raw retail transaction dataset
│   └── processed/                # KNIME output and category summary
├── knime-workflow/
│   └── retail_sales_etl/         # KNIME workflow files
├── python/
│   └── sales_analysis.ipynb      # Python category analysis
├── reports/
│   └── *.png                     # Exported visualizations
└── README.md
```

---

## 🚀 Outcome
This project demonstrates **workflow automation and ETL expertise**, 
combining KNIME pipelines with Python analysis to deliver insights 
suitable for **Data Analyst, Business Analyst and Analytics Engineer roles**.

---
*Dataset sourced from Kaggle Retail Sales Transaction Dataset.*
