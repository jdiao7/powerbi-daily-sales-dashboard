# Power BI Daily Sales Dashboard

This project analyzes daily sales data from a **Daily** coffee chain location in the Philippines using **Power BI**.

The dashboard is designed to be **fully dynamic and reusable**, allowing new months of data to be added without structural changes.  
**November is used as a sample period** in this repository because it is the most recent fully completed month with a consistent dataset.

---

## Project overview

The goal of this dashboard is to provide clear visibility into store performance by:
- Tracking key sales KPIs
- Monitoring daily sales trends
- Comparing third-party delivery platform revenue
- Supporting ongoing operational decision-making

The dashboard is suitable for recurring monthly reporting and can be refreshed as new data becomes available.

---

## Key KPIs

The following KPIs are dynamically calculated based on the selected date range:

- **Gross Sales** – Total sales before deductions  
- **Total Net Sales** – Net revenue after adjustments  
- **Grab Revenue** – Revenue generated via Grab delivery  
- **Food Panda Revenue** – Revenue generated via Food Panda  
- **Food Revenue** – In-store and food-only revenue totals  

All KPI cards update automatically when the date range is adjusted or new data is loaded.

---

## Trend analysis

### Daily Net Sales
A line chart showing net sales performance by day, allowing identification of:
- High-performing days
- Sales dips or anomalies
- Overall revenue momentum across a selected period

### Grab vs Food Panda Daily Revenue
A comparative line chart visualizing daily revenue from:
- Grab
- Food Panda

This enables quick evaluation of platform performance, demand patterns, and revenue contribution differences over time.

---

## Dashboard features

- Interactive **date range slicer**
- Dynamic KPI recalculation
- Multi-platform revenue comparison
- Clean, executive-ready visual layout
- Designed for ongoing monthly updates

---

## Sample data

This repository includes:
- `sample_output.csv` – Example dataset used to populate the dashboard  
- A screenshot preview of the dashboard output

The sample data reflects a completed reporting period but is representative of the structure used for all months.

---

## Tools used

- **Power BI** – Data modeling, DAX measures, and visualization  
- **Excel / CSV** – Source data format  

---

## Dashboard scalability

This dashboard is built to support:
- Additional months of data with no model changes
- Automatic KPI recalculation
- Ongoing operational and performance reporting

New data can be appended to the existing dataset, and all visuals and measures update accordingly.

---

## Notes

This project was created for analytical and portfolio purposes.  
All data has been sanitized and is used solely to demonstrate dashboard design, data modeling, and business analysis techniques.
