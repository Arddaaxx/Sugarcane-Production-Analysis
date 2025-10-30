# Sugarcane Production Analysis

**A comprehensive Exploratory Data Analysis (EDA) on global sugarcane production**

---

## Project Overview

This repository contains an EDA project that explores global sugarcane production with a focus on: production volume, land usage (hectares), and yield (tonnes per hectare) across countries and continents. The goal is to surface insights that can inform agricultural strategies, resource allocation, and yield optimization.

The analysis is implemented in a Jupyter Notebook (`Sugarcane_Production_Analysis.ipynb`) and includes data cleaning, exploratory visualizations, correlation analysis, and actionable findings.

---

## Table of Contents

* [Project Overview](#project-overview)
* [Key Questions](#key-questions)
* [Dataset](#dataset)
* [What I did (EDA Checklist)](#what-i-did-eda-checklist)
* [Key Findings](#key-findings)
* [How to run](#how-to-run)
* [Requirements](#requirements)
* [Structure of the repository](#structure-of-the-repository)
* [Future Work](#future-work)
* [Credits & Contact](#credits--contact)

---

## Key Questions

* Which countries and continents are the largest producers of sugarcane?
* How does production relate to land area cultivated (hectares) and yield (tonnes/hectare)?
* Are there noticeable trends, outliers, or regional patterns in production and yield?
* Which features should be prioritized when building predictive models for production or yield?

---

## Dataset

> Place a short note here linking to the dataset file or source (if public). If the dataset is private, indicate how a similar dataset can be obtained.

* Source: (e.g., FAO, national agricultural statistics, or a cleaned CSV provided in this repo)
* Primary columns used: `Country`, `Continent`, `Year`, `Production_tonnes`, `Area_hectares`, `Yield_t_per_ha`
* Timeframe: [specify years covered] (update accordingly)

---

## What I did (EDA Checklist)

1. **Data Loading & Inspection** — Reviewed schema, data types, and missing values.
2. **Cleaning & Preprocessing** — Handled missing values, standardized column names, converted units where necessary, and filtered for relevant years.
3. **Univariate Analysis** — Distribution plots, top-k producers, and summary statistics for production, area, and yield.
4. **Bivariate Analysis** — Scatter plots and correlation matrices to understand relationships (e.g., production vs area, yield vs production).
5. **Regional Analysis** — Aggregation by country and continent to detect geographic patterns and hotspots.
6. **Outlier Detection** — Identified anomalous records and investigated likely causes.
7. **Visualization** — Time series, bar charts, boxplots, and heatmaps to communicate patterns clearly.
8. **Insights & Recommendations** — Interpreted EDA results and suggested directions for modelling and agricultural strategy.

---

## Key Findings (summary)

* **Top producers:** A small set of countries contribute a large share of global production (list top 3–5 in the notebook).
* **Production vs Area:** Production generally increases with cultivated area, but yield (tonnes/hectare) explains variance in efficiency between countries.
* **Yield leaders:** Some regions achieve significantly higher yields — these are candidates for best-practice case studies.
* **Outliers & anomalies:** A few countries show unusually high/low yields relative to area — further investigation recommended (data quality or local practices).

(For full charts, tables and specific numeric results, see the notebook.)

---

## Requirements


```
pandas
matplotlib
seaborn
jupyter

```

Adjust as necessary — the notebook lists the exact imports at the top.



## Future Work

* Build predictive models for production / yield (regression models, ensemble methods).
* Incorporate weather, soil, and management practice data to improve predictions.
* Create an interactive dashboard to explore regional trends and scenario analysis.
* Perform time-series forecasting for year-on-year production changes.


