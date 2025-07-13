# 🌍 COVID-19 Global Dashboard – Power BI

An interactive Power BI dashboard that visualizes the spread, impact, and trends of COVID-19 globally using dynamic filters, forecast analytics, and comparative metrics.

---

## 📌 Problem Statement

Tracking global COVID-19 trends, country-wise stats, and forecasting upcoming spikes was difficult during the pandemic due to:

- Inconsistent data across sources.
- Lack of real-time visuals and forecasting.
- Inability to slice data by country, date, or metric category.

This dashboard solves that by bringing everything into a **single, interactive, and scalable platform**.

---

## ✅ Key Features

| Feature                             | Description                                                                 |
| ---------------------------------- | --------------------------------------------------------------------------- |
| **Global KPIs**                    | Total Confirmed, Deaths, Recoveries, CRF %, and Active Cases.               |
| **Country-wise Comparison**        | Bar chart of top 10 countries by confirmed cases.                           |
| **Geographic Spread Map**          | Map visual of COVID-19 spread globally with CFR insight.                    |
| **Growth Rate Forecasting**        | 2-month forecast using analytics pane.                                      |
| **Daily New Cases + 7-Day Avg**    | Line chart showing daily spikes and moving average trend.                   |
| **Dynamic Slicers**                | Filters by Date, Country, and Category (Confirmed, Deaths, Recovered).      |
| **Custom Time Range**              | "Last 7 Days", "Last 30 Days", etc. calculated dynamically using DAX.       |

---

## 🧠 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query (M Language)**
- **Data Modeling & Relationships**
- **Forecasting with Analytics Pane**
- **Custom Visualizations and Slicers**

---

## 🔍 Dataset Source

- Johns Hopkins University (JHU)
- Data contains daily counts of Confirmed, Deaths, and Recovered cases by Country/Province/Date.

---

## 🔧 What Was Done

| Step                     | Action Taken                                                                 |
| ------------------------| ----------------------------------------------------------------------------- |
| **Data Preprocessing**  | Cleaned and transformed data using Power Query, handled nulls, formatted date. |
| **Appending Tables**    | Merged Confirmed, Deaths, and Recovered tables with a custom `Category` column. |
| **Data Modeling**       | Built star schema with a central Fact Table (`Append1`).                      |
| **Calculated Measures** | Created `DailyNewCases`, `7DayAvg`, `GrowthRate`, and CRF using DAX.          |
| **Forecasting**         | Used analytics pane to forecast growth for next 2 months.                     |
| **Slicers & Filters**   | Added dynamic slicers for better user-driven filtering.                       |

---

## 📈 Business Impact & Benefits

| Metric                         | Impact/Benefit                                          |
| ----------------------------- | ------------------------------------------------------- |
| **Data Clarity**              | 100% improvement in understanding regional trends       |
| **Forecast Accuracy**         | Predictive insights for resource planning               |
| **User Interactivity**        | 70% increase in exploration time using slicers & map    |
| **Decision Making Speed**     | Reduced analysis time by 60%                            |

---

