# Bike Buyers – Customer Analysis Dashboard (Excel)

An end-to-end Excel analytics project that cleans a raw bike-buyers survey dataset, builds Pivot Tables, and turns them into an interactive one-page dashboard to understand *who* buys bikes and *why*.

## 📌 Project Overview

Retail and marketing teams often need a quick way to see which customer segments are most likely to buy a product. This project uses a real-world **"Bike Buyers"** customer survey dataset (demographic + lifestyle attributes) and walks it through the full Excel analytics workflow — from messy raw data to a decision-ready dashboard — without using any external BI tool, purely in Microsoft Excel.

## 🎯 Objective

- Clean and standardize a raw customer dataset so it is analysis-ready.
- Engineer a new feature (Age Brackets) to enable segment-level analysis.
- Use Pivot Tables to summarize purchasing patterns across income, gender, commute distance, and age.
- Visualize those patterns with PivotCharts.
- Combine everything into a single interactive Excel dashboard that answers: *which customer segments are most likely to purchase a bike?*

## 🗂️ Dataset

- **Domain:** Customer demographics & bike purchase behavior
- **Size:** ~1,000 unique customer records after cleaning
- **Fields:** ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Age Brackets *(engineered)*, Purchased Bike (Yes/No)

## 🛠️ Tools & Technologies

- **Microsoft Excel** – Data Cleaning, Pivot Tables, PivotCharts, Dashboard design
- Core Excel features used: duplicate removal, text standardization, derived/calculated columns, PivotTables, PivotCharts (bar & line), dashboard layout with linked charts

## 🔄 Project Workflow

The workbook is organized into 4 worksheets that mirror the analytics workflow:

| Sheet | Purpose |
|---|---|
| **Raw Data** | Original, unprocessed survey data exactly as received |
| **Cleaned Data** | Duplicate-free, standardized dataset with an added `Age Brackets` column, ready for analysis |
| **Pivot Table** | Pivot Tables summarizing income, commute distance, and age-bracket trends against bike purchases |
| **Dashboard** | Final interactive dashboard combining all PivotCharts into a single view |

### Data Cleaning Steps
- Removed duplicate customer records.
- Standardized inconsistent category labels (e.g., unified commute-distance labels into a consistent format).
- Verified column data types (numeric fields for Income/Age/Cars, categorical fields for the rest) for accurate aggregation.
- Engineered a new **Age Brackets** column (Adults / Middle-Aged / Seniors) from the raw `Age` field to allow segment-wise analysis.

## 📊 Dashboard Features

The dashboard brings together three PivotChart-driven views:

1. **Average Income by Gender vs. Purchase Status** (bar chart) – compares average income of buyers vs. non-buyers, split by gender.
2. **Bike Purchases by Commute Distance** (line chart) – shows how many customers bought a bike at each commute-distance range.
3. **Bike Purchases by Age Bracket** (line chart) – shows purchase counts across Adults, Middle-Aged, and Senior customers.

All charts are pivot-based, so they can be refreshed and re-filtered as the underlying data changes.

## 💡 Key Insights

- Customers who purchased a bike have a **higher average income** than those who didn't — the gap is much wider for **male** customers (₹58,908 vs ₹50,108) than for **female** customers (₹52,901 vs ₹51,849).
- Customers with a **short commute (0–1 miles and 2–5 miles)** show the **highest bike purchase counts**, suggesting bikes are being bought mainly for short, local commutes rather than long-distance travel.
- **Middle-Aged customers** are the largest buyer segment by far, both in absolute numbers and purchase share, making them the primary target group.
- Overall, the data suggests marketing efforts would be most effective if targeted at **middle-aged, short-commute customers**, with a secondary focus on higher-income male customers.


## 👤 Author
- Yuvraj Singh 

**Yuvraj Singh**
📧 yuvraj.raghav46@gmail.com | 🔗 [GitHub](https://github.com/Yuvraj-Singh0) | 🔗 [LinkedIn](https://linkedin.com/in/yuvraj-singh04)
