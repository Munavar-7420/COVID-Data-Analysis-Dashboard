<div align="center">

# 🦠 COVID-19 Data Analysis Dashboard

### Analyzing Global Pandemic Trends Using Python, Data Visualization, and Business Intelligence

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

</div>

---

## 📌 Project Overview

This project analyzes worldwide COVID-19 data to understand the spread of the pandemic, country-wise infection trends, mortality rates, recovery patterns, and regional impacts.

The analysis combines multiple COVID-19 datasets and visualizes key metrics using Python and Power BI dashboards to generate meaningful public health insights.

---

## 🎯 Objectives

✔ Analyze global COVID-19 spread

✔ Compare confirmed cases across countries

✔ Evaluate death and recovery rates

✔ Monitor daily and monthly trends

✔ Identify highly affected regions

✔ Create interactive dashboards

✔ Generate data-driven insights

---

## 🧰 Tools & Technologies

<p align="center">

<a href="https://www.python.org/">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50" height="50"/>
</a>

<a href="https://pandas.pydata.org/">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="50" height="50"/>
</a>

<a href="https://numpy.org/">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="50" height="50"/>
</a>

<a href="https://matplotlib.org/">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" width="50" height="50"/>
</a>

<a href="https://powerbi.microsoft.com/">
<img src="https://img.icons8.com/color/48/power-bi.png" width="50" height="50"/>
</a>

</p>

---

## 📂 Dataset

**Dataset:** Corona Virus Report

**Source:** https://www.kaggle.com/datasets/imdevskp/corona-virus-report

### Dataset Files

#### country_wise_latest.csv

- Country/Region
- Confirmed
- Deaths
- Recovered
- Active
- New Cases
- New Deaths
- WHO Region

#### covid_19_clean_complete.csv

- Province/State
- Country/Region
- Date
- Confirmed
- Deaths
- Recovered
- Active
- WHO Region

#### day_wise.csv

- Date
- Confirmed
- Deaths
- Recovered
- Active
- New Cases
- New Deaths
- New Recovered

#### full_grouped.csv

- Date
- Country/Region
- Confirmed
- Deaths
- Recovered
- Active
- WHO Region

#### usa_county_wise.csv

- County Information
- State
- Confirmed Cases
- Deaths

#### worldometer_data.csv

- Country/Region
- Population
- Total Cases
- Total Deaths
- Total Recovered
- Active Cases
- Total Tests
- WHO Region

---

## 📊 Dataset Summary

- 180+ Countries
- Global COVID-19 Statistics
- Daily Pandemic Tracking
- Regional Analysis
- Recovery & Mortality Metrics
- Population-Based Insights

---

## 🔄 Project Workflow

```text
COVID Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Data Integration
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Trend Analysis
      │
      ▼
Data Visualization
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights
```

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Missing Value Handling
- Duplicate Removal
- Date Formatting
- Country Standardization
- Feature Engineering
- Data Aggregation

---

## 📈 Analysis Performed

### Country-wise COVID Spread

- Top Countries by Confirmed Cases
- Active Cases Analysis
- Infection Growth Comparison

### Death vs Recovery Analysis

- Recovery Rate Calculation
- Mortality Rate Analysis
- Country Comparison

### Time Trend Analysis

- Daily Cases Trend
- Daily Death Trend
- Recovery Trend

### Regional Analysis

- WHO Region Comparison
- Continent-Level Analysis
- Population-Based Metrics

---

## 📊 Dashboard Features

### KPI Cards

- Total Confirmed Cases
- Total Recoveries
- Total Deaths
- Active Cases
- Recovery Rate

### Visualizations

- Country-wise Cases
- Death vs Recovery Rate
- Daily Trend Analysis
- Top Affected Countries
- WHO Region Analysis

### Interactive Features

- Date Filters
- Country Filters
- Region Slicers
- Drill-Down Analysis

---

## 📷 Dashboard Preview

### Global COVID Dashboard

<img width="1693" height="929" alt="Global Covid-19 Dashboard" src="https://github.com/user-attachments/assets/b40ca7ce-0a6a-4e70-a44b-3bbac7ec812f" />

### Country-wise Spread Analysis

<img width="1692" height="929" alt="Country-Wise Covid-19 Spread Analysis" src="https://github.com/user-attachments/assets/13a636ab-4e1c-45f6-be14-117a7bd3b941" />

### Death vs Recovery Dashboard

<img width="1692" height="930" alt="Covid-19 Death VS Recovery Dashboard" src="https://github.com/user-attachments/assets/d1c33045-f362-42a1-a44e-59670e8cb200" />

### Time Trend Visualization

<img width="1693" height="929" alt="Covid-19 Time Trend Visualization" src="https://github.com/user-attachments/assets/5c129c8f-0149-4d3e-82ae-7838372da8c3" />

---

## 💡 Key Insights

- Countries showed significantly different infection growth rates.
- Recovery rates improved substantially over time.
- Mortality rates varied by region.
- Pandemic waves are clearly visible in time-series trends.
- Testing volume influenced reported case counts.

---

## 📁 Repository Structure

```text
COVID-19-Data-Analysis-Dashboard/
│
├── Data/
│   ├── country_wise_latest.csv
│   ├── covid_19_clean_complete.csv
│   ├── day_wise.csv
│   ├── full_grouped.csv
│   ├── usa_county_wise.csv
│   └── worldometer_data.csv
│
├── Notebook/
│   └── COVID_Data_Analysis.ipynb
│
├── Dashboard/
│   └── COVID_Analysis_Dashboard.pbix
│
├── Pics/
│   ├── global-dashboard.png
│   ├── country-analysis.png
│   ├── recovery-dashboard.png
│   └── time-trend.png
│
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Improvements

- COVID Forecasting Models
- Time Series Forecasting
- Real-Time API Integration
- Interactive Web Dashboard
- Geospatial Mapping
- Machine Learning Predictions

---

## 👨‍💻 Author

**Munavar Patter**

Aspiring Data Analyst | Data Scientist

Python • Pandas • SQL • Power BI • Machine Learning
