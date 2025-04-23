# 🌫️ PM2.5 Pollution Level Analysis and Forecasting in Kazakhstan Cities (2023)

## 📌 Project Overview

This project focuses on analyzing and forecasting **PM2.5 pollution levels** across major cities in **Kazakhstan** for the year **2023**. It uses real-world data covering monthly PM2.5 concentrations, applies **data cleaning and visualization techniques**, and implements **machine learning models** to predict future pollution trends.

## 📁 Dataset

The dataset includes:
• Rank: The ranking of cities based on their annual average PM2.5 concentration (μg/m³).

• City: The name of the city.

• 2023: The average pollution index for the year 2023.

• Jan, Feb, Mar, Apr, May, Jun, Jul, Aug, Sep, Oct, Nov, Dec: Monthly pollution levels from January to December.

• Country: The corresponding country for each city.

> **Source**: Aggregated dataset with air quality data from Asian cities, including Kazakhstan.
Link for Kaggle dataset https://www.kaggle.com/datasets/shruthiiiee/asia-2023-air-report-2000-cities

---

## 🧹 Steps Performed

### 1. Data Cleaning
- Checked for missing values and filled using **mean** or **linear interpolation**
- Removed duplicates
- Converted columns to appropriate data types
- Standardized city names and month formats

### 2. Exploratory Data Analysis (EDA)
- Visualized monthly PM2.5 trends using **line plots**
- Compared city-wise annual averages with **bar charts**
- Heatmaps of seasonal variation