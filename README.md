# Power BI Daily Sales Dashboard

An interactive **Power BI dashboard** built to analyze daily sales performance for a **Daily coffee chain location in the Philippines**.

The dashboard is designed to be **fully dynamic and reusable**, allowing new months of data to be added without structural changes.  
November is used as a sample period in this repository because it represents the most recent fully completed month with a consistent dataset.

---

## 📊 Dashboard Overview

![Power BI Dashboard Preview](screenshots/dashboard_overview.png)

This dashboard provides a high-level view of store performance along with channel-level comparisons and daily sales trends.

---

## 📌 Key Metrics (KPIs)

The dashboard tracks the following core KPIs:

- **Gross Sales**
- **Total Net Sales**
- **Grab Revenue**
- **Food Panda Revenue**
- **In-store Food Revenue**

All KPIs are dynamically calculated and automatically update based on the selected date range.

---

## 📈 Visualizations

- **Daily Net Sales Trend**  
  Line chart showing net sales performance by day

- **Grab vs Food Panda Daily Revenue**  
  Comparative line chart analyzing third-party delivery platform performance

- **Dynamic Date Slicer**  
  Enables analysis across any completed or in-progress month

---

## 🧹 Data Preparation & Modeling

- Source data originated from **daily sales reports** with inconsistent formatting and excess columns
- Data cleaning and transformation performed directly in **Power BI (Transform Data)** using **Power Query**
- Reduced **200+ raw columns** into a KPI-focused analytical model
- Standardized date fields and consolidated sales channels
- Created calculated measures and date logic to support time-based analysis

### Power Query Transformation Preview

![Power Query Cleaned Data](screenshots/power_query_cleaned_data.png)

---

## 💡 Operational Insights Enabled

This dashboard is designed to surface actionable insights such as:

- The relative contribution of **in-store food sales vs third-party delivery platforms**
- Day-to-day variability in **net sales performance**
- Differences in revenue patterns between **Grab and Food Panda**
- The impact of discounts and platform fees by comparing **gross vs net sales**
- Ongoing month-over-month performance as new data is added

While November is used as a representative reporting period, the dashboard is built to continuously surface these insights as additional data becomes available.

---

## 🗂️ Repository Contents

```text
powerbi-daily-sales-dashboard/
├── README.md
├── screenshots/
│   ├── dashboard_overview.png
│   └── power_query_cleaned_data.png
└── sample_data/
    └── raw_daily_sales_original.xlsx
