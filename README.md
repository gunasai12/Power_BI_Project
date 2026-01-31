# 📊 Real-Time E-Commerce Revenue Intelligence System

![Power BI](https://img.shields.io/badge/PowerBI-Analytics-yellow)
![Excel](https://img.shields.io/badge/Data-Excel-green)
![DAX](https://img.shields.io/badge/Language-DAX-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)

> Production-style Business Intelligence system built using Power BI to transform raw e-commerce transactional data into executive-level revenue insights.

---

## 🎯 Why This Project Matters

E-commerce businesses generate large volumes of transactional data.  
Without structured analytics, decision-makers lack visibility into:

- Revenue concentration
- Market performance
- Category contribution
- Shipping cost impact
- Profit optimization opportunities

This project builds a centralized, interactive dashboard to address those challenges using data modeling and DAX-driven KPI evaluation.

---

## 📊 Live System Metrics

- 💰 **Total Sales:** 12.64M  
- 📈 **Total Profit:** 1.47M  
- 📦 **Total Quantity Sold:** 178K  
- 🚚 **Total Shipping Cost:** 1.35M  
- 🌍 **Markets Covered:** 7  
- 🛒 **Product Categories:** 3  

---

## 🖥 Dashboard Preview

<p align="center">
  <img src="./dashboard_preview.gif" width="950">
</p>

---

## 🚀 Quick Setup

### Clone the Repository

```bash
git clone https://github.com/gunasai12/Power_BI_Project.git
cd Power_BI_Project
Run the Dashboard
Open E Commere Report.pbix in Microsoft Power BI Desktop

Reconnect to ECOMM DATA.xlsx if prompted

Explore interactive visuals and filters

📈 Dashboard Capabilities
Executive KPI Monitoring
Total Sales

Total Profit

Total Quantity

Shipping Cost

Geographic Intelligence
Sales by Country

Sales by State

Revenue concentration visualization

Category Analytics
Technology

Furniture

Office Supplies

Comparative revenue performance

Market Segmentation
APAC

EU

US

LATAM

EMEA

Africa

Canada

Shipping Performance Analysis
Standard Class

Second Class

First Class

Same Day

Shipping cost impact tracking

Interactive Features
Category slicer

Sub-category slicer

Dynamic filtering across visuals

🧠 Data Architecture
Data Source
ECOMM DATA.xlsx

Data Model Design
Central Sales Fact Table

Supporting Dimension Tables:

Country

Market

Category

Ship Mode

Model optimized for:

Accurate aggregations

Efficient filtering

Scalable reporting

📐 Core DAX Implementation
Total Sales = SUM('ECOMM DATA'[Sales])
Total Profit = SUM('ECOMM DATA'[Profit])
Total Quantity = SUM('ECOMM DATA'[Quantity])
Total Shipping Cost = SUM('ECOMM DATA'[Shipping Cost])
Additional analytical calculations include:

Country revenue contribution %

Market share analysis

Category comparison metrics

Profit vs shipping cost evaluation

🛠 Technology Stack
Business Intelligence
Microsoft Power BI

DAX (Data Analysis Expressions)

Data Processing
Microsoft Excel

Data Cleaning & Structuring

Visualization Components
KPI Cards

Donut Charts

Tree Maps

Bar Charts

Interactive Slicers

📦 Repository Structure
Power_BI_Project/
│
├── E Commere Report.pbix
├── ECOMM DATA.xlsx
├── dashboard_preview.gif
├── dashboard_preview.png
└── README.md
💼 Business Value Delivered
This dashboard enables:

Executive revenue monitoring

Market performance benchmarking

Category profitability evaluation

Shipping efficiency tracking

Data-driven strategic decision-making

🔮 Future Enhancements
Time-series revenue trend analysis

Year-over-Year growth comparison

Profit margin forecasting

Power BI Service deployment with scheduled refresh

Row-Level Security implementation

Advanced DAX performance modeling

📌 Resume-Ready Impact Points
Designed and developed an executive-level Power BI dashboard analyzing 12.6M+ revenue data

Implemented DAX-based KPI tracking and market share analytics

Structured a clean BI data model for optimized performance

Delivered actionable insights across geography, category, and logistics

Transformed raw Excel data into a scalable business intelligence solution

👨‍💻 Author
Anumulapally Gunasai
B.Tech Final Year Student
Aspiring Data Analyst | AI & ML Engineer

Focused on building scalable data-driven systems that convert raw data into strategic intelligence.


---

This is fully GitHub-ready.

If you don’t yet have `dashboard_preview.gif`, replace this line:

```html
<img src="./dashboard_preview.gif" width="950">
with:

<img src="./dashboard_preview.png" width="950">
