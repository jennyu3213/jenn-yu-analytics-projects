# Cyclistic Bike Share Case Study

## Project Overview
This case study analyzes bike-sharing usage patterns between **annual members** and **casual riders** using Cyclistic (Divvy) trip data.

The objective is to identify behavioral differences between the two user types and derive insights that could support data-driven business and marketing decisions.

---

## Data Source
- Divvy Trips data
- Q1 2019 and Q1 2020 datasets

The datasets include information such as ride start and end times, station names, and user type.

> Note: Raw data files are not included in this repository due to size and licensing considerations.

---

## Data Preparation
Key data cleaning and transformation steps include:
- Aligning column names across 2019 and 2020 datasets
- Converting ride duration to minutes
- Removing invalid, negative, and duplicate rides
- Engineering new features such as:
  - Ride length
  - Day of week
  - Time of day

---

## 📈 Analysis & Methods
The analysis focuses on:
- Comparing average ride length by user type
- Examining weekly ride patterns for members vs. casual riders
- Identifying peak riding hours
- Visualizing commute patterns using heatmaps

R was used for data cleaning, transformation, analysis, and visualization.

---

## Key Insights
- Casual riders tend to have longer ride durations than annual members
- Annual members show stronger weekday commuting patterns
- Casual rider activity increases significantly on weekends
- Peak riding hours differ between the two user groups, reflecting different usage motivations

---

## Tools Used
- R
  - tidyverse
  - lubridate
  - ggplot2
- R Markdown

---

## Files in This Folder
- `cyclistic_analysis.Rmd`  
  Full analysis code, including data cleaning, analysis, and visualizations

---

## Notes
This project was completed as part of a data analytics portfolio and is intended to demonstrate analytical thinking, data preparation skills, and clear communication of insights.

