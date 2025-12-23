# Power BI Daily Sales Dashboard

This project analyzes daily sales data from a **Daily coffee chain location in the Philippines** using Power BI.  
The dashboard focuses on **November**, the most recent fully completed month with a consistent and complete dataset.

The goal of the project is to transform raw, operational sales data into clear, business-focused insights for store owners and managers.

---

## Project overview

The raw dataset consisted of daily sales reports exported from point-of-sale systems and delivery platforms.  
It contained **200+ columns**, many of which were operational, redundant, or inconsistent.

This project focused on:
- Cleaning and restructuring messy real-world sales data
- Designing a usable analytical model
- Building KPI-driven dashboards for business decision-making

---

## Key KPIs (November)

The dashboard highlights the following performance metrics for November:

- **Gross Sales**
- **Total Net Sales**
- **Grab Revenue**
- **Foodpanda Revenue**
- **Food Revenue**

These KPIs provide a high-level snapshot of store performance across in-store and third-party delivery channels.

---

## Sales trend analysis

The dashboard includes:
- **Daily Net Sales** trend to visualize revenue fluctuations throughout the month
- A comparative **Grab vs Foodpanda daily revenue** chart to analyze delivery platform performance

This allows stakeholders to quickly identify:
- High- and low-performing days
- Channel contribution patterns
- Variability in third-party delivery revenue

---

## Data preparation (Power Query)

Key data preparation steps included:
- Removing unused and redundant columns
- Standardizing date and time fields
- Handling missing values and non-operational days
- Restructuring the dataset to support KPI-level analysis
- Consolidating sales channels into an analysis-ready fact table

Power Query was used extensively to ensure the final dataset was reliable and consistent.

---

## Data modeling & measures (DAX)

- Built a dedicated **date table** to support time-based analysis
- Created DAX measures for:
  - Gross and net sales
  - Channel-specific revenue (Grab and Foodpanda)
  - Daily and monthly aggregations
- Ensured relationships supported accurate filtering and comparisons

---

## Dashboard design

The dashboard was designed with **non-technical business users** in mind:
- Clean KPI cards for quick performance assessment
- Simple, readable trend visuals
- Focus on clarity and actionable insights rather than technical complexity

---

## Files in this repository

- `screenshots/`  
  Screenshots of the Power BI dashboard and key visuals.

> Note: The Power BI `.pbix` file and raw business data are not included to protect sensitive information.
