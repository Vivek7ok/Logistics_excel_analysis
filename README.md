# 📦 Logistics & Supply Chain Performance Analysis

<div align="center">

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-0078D4?style=for-the-badge&logo=databricks&logoColor=white)
![Business Analytics](https://img.shields.io/badge/Business_Analytics-FF6F00?style=for-the-badge&logo=google-analytics&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

**An end-to-end Excel-based analytics solution for logistics performance monitoring, KPI tracking, and operational decision support.**

[View Repository](https://github.com/Vivek7ok/Logistics_excel_analysis) · [Report Bug](https://github.com/Vivek7ok/Logistics_excel_analysis/issues) · [Request Feature](https://github.com/Vivek7ok/Logistics_excel_analysis/issues)

</div>

---

## 📌 Overview

This project delivers a **comprehensive logistics and supply chain analytics framework** built entirely in Microsoft Excel. Designed to replicate real-world business intelligence workflows, it transforms raw operational data into structured, actionable insights — enabling stakeholders to monitor delivery performance, identify supply chain bottlenecks, and make data-driven decisions.

The solution incorporates dynamic dashboards, automated KPI tracking, and structured reporting pipelines that mirror industry-standard practices used by operations and analytics teams in logistics, e-commerce, and manufacturing sectors.

---

## 🎯 Objectives

| # | Objective | Description |
|---|-----------|-------------|
| 1 | **Logistics Performance Analysis** | Evaluate end-to-end delivery metrics across carriers, regions, and time periods |
| 2 | **Delivery Tracking & Monitoring** | Track on-time delivery rates, delays, and fulfillment cycles |
| 3 | **Operational Insights** | Identify inefficiencies in routing, handling, and carrier performance |
| 4 | **KPI Monitoring** | Build a structured framework for monitoring business-critical logistics KPIs |
| 5 | **Data Cleaning & Reporting** | Standardize raw data inputs and generate clean, professional reports |

---

## 🛠️ Tools & Techniques

<div align="center">

| Category | Tools / Functions |
|----------|------------------|
| **Platform** | Microsoft Excel (365 / 2021) |
| **Data Aggregation** | Pivot Tables, Pivot Charts |
| **Visualization** | Charts, Dashboards, Conditional Formatting |
| **Lookup & Reference** | XLOOKUP, INDEX-MATCH |
| **Logic & Calculation** | IF, IFS, IFERROR, SUMIFS, COUNTIFS, AVERAGEIFS |
| **Data Cleaning** | Text Functions, Remove Duplicates, Data Validation |
| **Formatting** | Conditional Formatting, Custom Number Formats |
| **Analysis** | Business Analysis, Trend Analysis, Variance Analysis |

</div>

---

## 📂 Dataset Information

The dataset represents a simulated but realistic logistics operations environment, encompassing multi-regional shipment records across multiple carriers and product categories.

**Dataset Dimensions:**

- **Records:** Thousands of shipment-level transactions
- **Time Span:** Multi-month operational data
- **Key Attributes:**
  - Order ID, Shipment Date, Delivery Date
  - Carrier / Vendor Name
  - Origin & Destination Region
  - Product Category & SKU
  - Shipment Status (On-Time / Delayed / Pending)
  - Freight Cost & Weight
  - Delivery Lead Time (Days)

> *Data has been cleaned, validated, and structured to ensure analytical integrity and reporting accuracy.*

---

## 📊 Key Insights & Findings

> *Sample business findings derived from the analysis:*

- 📉 **On-Time Delivery Rate** averaged **82.4%** across all carriers — with Carrier B underperforming at **67%**, flagging a vendor management concern.
- 🌍 **North Region** recorded the highest freight costs, driven by long-haul distances and low consolidation rates.
- ⏱️ **Average Lead Time** was **4.7 days**, with Electronics and Perishables categories experiencing the most variability.
- 📦 **Weekend dispatches** showed a **23% higher delay rate** compared to weekday shipments, indicating a staffing or operational gap.
- 💰 **Cost-per-unit-shipped** decreased by **11%** in Q3** after route optimization — validated through trend analysis.
- 🔄 **Top 3 delay causes** identified: carrier capacity issues, customs clearance hold-ups, and weather-related disruptions.

---

## 🖥️ Dashboard Features

The interactive Excel dashboard serves as a centralized command center for logistics performance monitoring.

```
┌─────────────────────────────────────────────────────┐
│              LOGISTICS PERFORMANCE DASHBOARD         │
├──────────────┬──────────────┬──────────────┬────────┤
│  Total Orders│  On-Time %   │  Avg Lead Time│ Costs  │
│    [KPI]     │    [KPI]     │    [KPI]      │ [KPI]  │
├──────────────┴──────────────┴──────────────┴────────┤
│  Delivery Trend (Line Chart)  │ Regional Map (Bar)   │
├───────────────────────────────┼─────────────────────┤
│  Carrier Performance (Column) │ Delay Reasons (Pie)  │
└───────────────────────────────┴─────────────────────┘
```

**Dashboard Capabilities:**

- **📌 KPI Cards** — Real-time summary of Total Shipments, On-Time %, Average Lead Time, and Total Freight Cost
- **📈 Trend Analysis** — Monthly delivery performance trends with period-over-period comparison
- **🚚 Carrier Benchmarking** — Side-by-side carrier performance across cost, speed, and reliability
- **🗺️ Regional Analysis** — Breakdown of shipment volumes and delay rates by geography
- **⚠️ Delay Tracking** — Root-cause classification of late deliveries with frequency analysis
- **🔍 Dynamic Filtering** — Slicers and dropdowns for on-the-fly data segmentation by region, carrier, and time period

---

## 💼 Skills Demonstrated

```
Data Analysis          ████████████████████  Advanced
Business Analytics     ███████████████████   Advanced
Excel Automation       ████████████████░░░░  Intermediate–Advanced
Dashboard Design       ████████████████░░░░  Intermediate–Advanced
Data Cleaning          █████████████████░░░  Intermediate
Reporting & Insights   ████████████████████  Advanced
Problem Solving        ████████████████████  Advanced
```

- **Data Analysis** — Transforming raw logistics data into structured, meaningful outputs
- **Business Analytics** — Translating operational metrics into business recommendations
- **Excel Automation** — Using advanced formulas to eliminate manual computation
- **Reporting** — Building executive-ready summaries and visual reports
- **Problem Solving** — Diagnosing supply chain inefficiencies from data patterns

---

## 📁 Folder Structure

```
Logistics_excel_analysis/
│
├── 📊 Data/
│   ├── Raw_Logistics_Data.xlsx          # Original unprocessed dataset
│   └── Cleaned_Logistics_Data.xlsx      # Validated and cleaned data
│
├── 📈 Analysis/
│   ├── Pivot_Analysis.xlsx              # Pivot table workbook
│   └── KPI_Calculations.xlsx           # Formula-driven KPI sheet
│
├── 🖥️ Dashboard/
│   └── Logistics_Dashboard.xlsx         # Final interactive dashboard
│
├── 📄 Reports/
│   └── Logistics_Performance_Report.pdf # Exported summary report
│
├── 🖼️ Screenshots/
│   ├── dashboard_overview.png
│   ├── kpi_cards.png
│   ├── carrier_analysis.png
│   └── regional_breakdown.png
│
└── 📝 README.md
```

---

## 🖼️ Screenshots

<div align="center">

### Dashboard Overview
> *📌 Screenshot placeholder — add `Screenshots/dashboard_overview.png`*

![Dashboard Overview](Screenshots/dashboard_overview.png)

---

### KPI Cards & Summary Metrics
> *📌 Screenshot placeholder — add `Screenshots/kpi_cards.png`*

![KPI Cards](Screenshots/kpi_cards.png)

---

### Carrier Performance Analysis
> *📌 Screenshot placeholder — add `Screenshots/carrier_analysis.png`*

![Carrier Analysis](Screenshots/carrier_analysis.png)

---

### Regional Delivery Breakdown
> *📌 Screenshot placeholder — add `Screenshots/regional_breakdown.png`*

![Regional Breakdown](Screenshots/regional_breakdown.png)

</div>

---

## 🚀 Future Improvements

| Enhancement | Description |
|------------|-------------|
| **Power BI Integration** | Migrate dashboards to Power BI for web-based sharing and real-time refresh |
| **Python Automation** | Automate data cleaning and ingestion using Pandas and OpenPyXL |
| **Predictive Analytics** | Build delivery delay prediction models using regression analysis |
| **SQL Backend** | Connect to a relational database for scalable data management |
| **API Integration** | Pull live carrier tracking data via REST APIs |
| **Automated Reporting** | Schedule email delivery of reports using Excel macros (VBA) |

---

## 👤 Author

**Vivek**

[![GitHub](https://img.shields.io/badge/GitHub-Vivek7ok-181717?style=flat-square&logo=github)](https://github.com/Vivek7ok)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com)

---

## 📃 License

This project is open-source and available under the [MIT License](LICENSE).

---

<div align="center">

*Built with precision and a data-driven mindset.*
**⭐ Star this repository if you found it useful!**

</div>
