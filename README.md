# 📊 COVID-19 Global Data Analysis

This project provides an in-depth analysis of global COVID-19 trends using time-series datasets of confirmed, recovered, and death cases. By visualizing pandemic growth over time and comparing different countries, it aims to build a clear understanding of how COVID-19 spread and evolved worldwide.

---

## 🌟 Project Motivation

Understanding COVID-19 dynamics is essential for:

✅ Guiding public health policies  
✅ Identifying countries with faster or slower recovery  
✅ Visualizing the impact on a global scale

---

## 🗂️ Datasets

The project uses three official time-series datasets from Johns Hopkins University:

- **Confirmed Cases**: `time_series_covid19_confirmed_global.csv`  
- **Recovered Cases**: `time_series_covid19_recovered_global.csv`  
- **Death Cases**: `time_series_covid19_deaths_global.csv`

Each dataset contains daily cumulative counts by country/region from the start of the pandemic.

---

## 🎯 Objectives

- 📌 Clean and preprocess messy time-series data
- 📌 Aggregate cases at the country level
- 📌 Create interactive and static visualizations for:
  - Global trends
  - Country-wise comparisons
  - Recoveries vs deaths analysis
  - Top 20 countries heatmap

---

## 📈 Key Features

✅ Data cleaning with pandas  
✅ Grouping provinces/states into countries  
✅ Transposing data for time-series analysis  
✅ Visual storytelling with matplotlib & seaborn  
✅ Easy-to-follow code structure

---

## 🖼️ Example Visualizations

### 🌍 Global Cumulative Trends
Line plot of total confirmed, recovered, and deaths worldwide over time.

### 📊 Country Comparison
Line charts comparing COVID-19 cases across top affected countries (e.g., US, India, Brazil, Russia, UK).

### 🟢 Recoveries vs Deaths
Area chart showing the difference between total recoveries and deaths.

### 🔥 Top 20 Countries Heatmap
Heatmap of confirmed cases for the 20 most affected countries at the latest date.

---

## ✅ Requirements

- Python 3.6+
- Required Python packages:
  ```bash
  pip install pandas matplotlib seaborn
