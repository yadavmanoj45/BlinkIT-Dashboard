# BlinkIT-Dashboard
# 📊 Blinkit Grocery Sales Dashboard – Power BI Project

## 🌟 Project Overview
The **Blinkit Grocery Sales Dashboard** is an interactive Business Intelligence dashboard built using **Power BI Desktop** to analyze retail grocery sales data.  
It provides actionable insights into **outlet performance, product categories, ratings, and sales trends (2012–2022)** through dynamic visuals and slicer-based filtering.

This project showcases **data transformation, DAX measures, KPI analysis, and user-friendly UI navigation** for retail analytics.

---

## 🚀 Key Insights & KPIs
- 💰 **Total Sales** → `$1.20M`
- 🛍 **Total Items Sold** → `8,523`
- 📉 **Average Sales** → `$141`
- ⭐ **Average Rating** → `3.9`
- 📈 **Outlet Establishment Sales Trend** (2012 → 2022)
- 🗂 **Sales Analysis by:**
  - Outlet Location (Tier 1, Tier 2, Tier 3)
  - Outlet Size (Small, Medium, High)
  - Item Type (Dairy, Fruits, Frozen Food, Snacks, etc.)
  - Fat Content (Low Fat, Regular)
- 🔁 **Navigation Panel** → Refresh ↻ | Back ◀ | Info ℹ
- 🎨 **Modern UI inspired by Blinkit branding**

---

## 🧰 Tech Stack & Tools Used
| Tools | Purpose |
|------|--------|
| **Power BI Desktop** | Dashboard & Visualization |
| **Power Query** | Data Cleaning & Transformation |
| **DAX** | Dynamic Measures & KPI Calculations |
| **Cards, Donuts, Bars, Tables, Area Chart** | Visual Components |

---

## 📌 DAX Measures Included
```DAX
Total Sales = SUM('Blinkit Grocery Data'[Sales])

Avg Sales = AVERAGE('Blinkit Grocery Data'[Sales])

No of Items = COUNTROWS('Blinkit Grocery Data')

Avg Ratings = AVERAGE('Blinkit Grocery Data'[Rating])

