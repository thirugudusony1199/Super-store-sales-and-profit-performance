# 🛒 Retail Sales Forecasting & Inventory Optimization — Superstore

## 📌 Overview
End-to-end retail analytics using the popular **Superstore** dataset. Combines **Python (Jupyter)** for EDA + basic forecasting and **Tableau** for interactive dashboards.

**What’s included**
- Data prep with standardized fields and dates
- KPIs: Revenue, Profit, Avg Order Value, Orders
- Visuals: monthly trend, category/sub-category, region performance
- Simple moving-average forecast and **inventory ABC + reorder-point helper**
- Tableau-ready CSV exports

## 📂 Structure
```
Retail-Superstore-Analytics/
│── data/                            # Sample - Superstore.csv (place here)
│── exports/                         # CSVs for Tableau
│── tableau/                         # .twbx + screenshots
│── Retail_Superstore_Analytics.ipynb
│── README.md
```
## 🚀 Run
1. Put `Sample - Superstore.csv` in `data/`
2. Install deps:
   ```bash
   pip install pandas matplotlib
   ```
3. Run notebook and open Tableau on the CSVs in `exports/`.

## 📊 Suggested Tableau Dashboards
- **Executive KPIs:** revenue, profit, AOV, orders (monthly)
- **Category Performance:** category & sub-category sales/profit (Pareto)
- **Regional Insights:** sales vs profit by region/state
- **Forecast View:** actual vs MA(3)

## 🧠 Notes
- Forecast is illustrative. For production, consider ARIMA/Prophet and promo/seasonality features.
- Inventory helper uses sub-category as item proxy if SKUs aren’t present.

