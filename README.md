![Azure Maps Cover](azure_maps_cover.png)

---

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-blue?logo=Power%20BI)](https://app.powerbi.com/...) 
[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?logo=GitHub)](https://github.com/arielovimag/adventureworks-bi-portfolio)
[![SQL Server](https://img.shields.io/badge/SQL%20Server-Database-red?logo=Microsoft%20SQL%20Server)]()
[![Azure Maps](https://img.shields.io/badge/Azure-Maps-blue?logo=Microsoft%20Azure)]()

# 🚀 Business Intelligence Portfolio – (Phase 2)

## 📊 Regional Sales Performance with Azure Maps – Adventure Works Dataset

This project represents Phase 2 of my BI Portfolio development, focusing on advanced geospatial analysis, data storytelling, and enriched dynamic narratives using:

✅ Power BI  
✅ Azure Maps  
✅ DAX Measures  
✅ Smart Narrative AI  
✅ Interactive Drillthrough  
✅ Decomposition Tree  
✅ Hierarchies: Country ➔ State ➔ City  
✅ Dynamic Top Reseller & Revenue measures  
✅ Advanced Crossfilter Management
✅ Dynamic Custom Tooltips

This second phase builds directly on the full data model and logic of the Executive Sales Dashboard (Phase 1).

---

## 🔗 Live Power BI Report

👉 [Click here to view the full interactive report]([PUBLIC-POWER-BI-SERVICE-LINK](https://app.powerbi.com/view?r=eyJrIjoiMDEzYTZmNjMtYjNjMS00YzUyLTlhOWEtODY4ZmY4ZmZjZmRiIiwidCI6IjQwOWY3ZjkzLTQ0N2EtNDBiYi05YzVjLWQ1MjI1M2E1ZjM5YiIsImMiOjZ9))

---

## 🔎 Dataset

- **Source**: Simulated AdventureWorks Reseller Sales Dataset
- **Model type**: Star Schema with fact and dimension tables:
  - Fact Table: `Sales_data`
  - Dimensions: `Reseller_data`, `Customer_data`, `Product_data`, `Sales_Territory_data`, `Date_Query`, `Sales_Order_data`

---

## 🗺️ Data Modeling

- Cleaned surrogate keys with `-1` unknown keys using Power Query M transformations
- Applied data enrichment for state/province hierarchies
- Managed cross-filtering for slicers and visual interactions
- Dynamic DAX ranking for Top State, Top City and Top Reseller

---

## 📈 Key Visualizations

- Azure Maps with dynamic geographic selection  
- Sales by Location (Country > State > City)  
- Decomposition Tree for Product Category/Subcategory/Product  
- KPI Cards with:
  - Total Revenue
  - Total Profit
  - Profit Margin
  - Average Ticket
  - Units Sold
  - Top Performing State & Reseller
- Fully automated Smart Narrative for dynamic data storytelling

---

## 🎯 Learning Objectives

- Complex filter context evaluation in DAX
- Storytelling through dynamic narratives
- Business scenario simulation for recruiters:
  - CPG / Retail / Supply Chain Performance
  - Sales Regional Optimization

---

## 📊 Key Features

- 🌐 **Dynamic Geographical Analytics** using Azure Maps with State → City drilldown.
- 🎯 **Dynamic Custom Tooltips** displaying detailed key metrics for selected locations (Revenue, Profit, Orders, Units, Profit Margin, Average Ticket).
- 💡 **Dynamic Smart Narrative** fully integrated with slicer selections and filter context for real-time contextual storytelling.
- 📈 **Top State and Top Reseller DAX Measures** dynamically adapting to any country-level filter applied.
- 🔎 Interactive **Decomposition Tree** to analyze sales by Category, Subcategory, and Product.
- 📊 **Fully synchronized slicers** to simulate regional performance monitoring.
- 🏷 **Data Mining Process** includes handling of unlinked foreign keys (-1 values), ensuring data integrity and relationship consistency.
- 🚀 Optimized for recruiter-friendly navigation with dedicated GitHub structure.

---

## 📄 Data Dictionary

| Table | Key Fields | Description |
| --- | --- | --- |
| Sales_data | Total Revenue, Profit, Orders | Main fact table |
| Reseller_data | Reseller, City, State | Reseller hierarchy |
| Customer_data | Customer, City | Customer hierarchy |
| Product_data | Category, Subcategory, Product | Product master |
| Sales_Territory_data | Region, Country | Regional mapping |
| Date_Query | Calendar hierarchy | Time intelligence |

---

## 💡 Next Steps

In Phase 3 I will integrate:

- 🔮 Predictive forecasting models (Python/R)
- 🧠 AI-powered anomaly detection
- 🎯 Supply Chain scenario simulations

---

## 🔗 Project Links

- 🎯 [GitHub Master Portfolio](https://github.com/arielovimag/adventureworks-bi-portfolio)
- 📊 [Power BI Service (Public Link)](https://app.powerbi.com/view?r=eyJrIjoiMDEzYTZmNjMtYjNjMS00YzUyLTlhOWEtODY4ZmY4ZmZjZmRiIiwidCI6IjQwOWY3ZjkzLTQ0N2EtNDBiYi05YzVjLWQ1MjI1M2E1ZjM5YiIsImMiOjZ9)

---

## 📩 Contact

> **Ariel Oviedo Maglione**
> 💻 Data Analyst | BI Analyst
> 📞 (+34) 645584506  
> 📧 arielovimag@gmail.com  
> 💼 [LinkedIn Profile](https://www.linkedin.com/in/arielovimag/)

---

