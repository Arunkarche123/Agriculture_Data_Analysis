#  🌾Agriculture Mandi Price Analytics & Forecasting

## 📌 Overview

An End-to-End Data Analytics project that analyzes agricultural mandi prices across India by integrating government market data, geolocation, and weather information. The project follows a complete ETL pipeline using Python and prepares data for SQL analysis and interactive Power BI dashboards.

---

## 🎯 Problem Statement

Agricultural mandi price data is available from government sources but lacks geographical and weather information, making location-based and weather-based analysis difficult.

This project integrates multiple datasets into a single analytical dataset to provide meaningful business insights.

---

## 🛠 Tech Stack

- Python
- Pandas
- SQL Server
- Power BI
- Excel
- Open-Meteo API
- Data.gov.in API

---

## 📂 Project Workflow

```
API Data Collection
        ↓
Market Geocoding
        ↓
Weather Data Collection
        ↓
Data Cleaning & Validation
        ↓
Data Merging
        ↓
Master Dataset
        ↓
Data Preprocessing
        ↓
Feature Engineering
        ↓
EDA
        ↓
SQL Analysis
        ↓
Power BI Dashboard
```

---

## 📊 Datasets

|        Dataset       |  Rows |             Purpose             |
|----------------------|-------|---------------------------------|
| AGMARKNET Price Data | 9,049 |        Commodity prices         |
|  Market Geolocation  | 1,391 |      Latitude & Longitude       |
|     Weather Data     | 1,391 | Temperature, Rainfall, Humidity |

---

## 📦 Master Dataset

- **Rows:** 9,049
- **Columns:** 17

Includes:

- Market Information
- Commodity Prices
- Geographic Coordinates
- Weather Information

---

## 📁 Project Structure

```
01_API_Data_Collection.ipynb
02_Geocoding.ipynb
03_Weather_Data.ipynb
04_Data_Cleaning_Validation.ipynb
05_Data_Merging.ipynb
06_Data_Preprocessing.ipynb
07_Feature_Engineering_EDA.ipynb
08_SQL_Queries.sql
09_PowerBI_Dashboard.pbix
```

---

## 🚀 Upcoming Analysis

- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis
- SQL Analytics
- Power BI Dashboard
- Business Insights

---

## 👨‍💻 Author

**Arun Karche**

Aspiring Data Analyst | Python | SQL | Power BI | Excel
