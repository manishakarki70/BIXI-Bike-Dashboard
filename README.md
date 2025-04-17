# 🚲 BIXI-Montréal Usage Dashboard

**BIXI** is a popular bike-sharing service in Montréal, Québec, and it's one of North America's most successful bike-sharing systems. BIXI provides public bicycles that people can rent short-term using docking stations spread throughout the city, especially from spring to fall.

---

## 📌 Project Overview

This dashboard analyzes public bike usage in Montréal (BIXI) to uncover seasonal trends, high and low usage stations, ride durations, peak hours, and how weather conditions affect cycling behavior. The goal is to generate actionable insights that could inform city planners and operational teams.

---

## 📊 Key Insights & Features

- 📈 **Total Rides**, **Average Duration**, and **% Change vs Previous Month**
- 📆 **Most Active Day** and 🕐 **Peak Ride Hours**
- 📍 **Top 5 Most Used** & **Bottom 5 Least Used** Stations
- 🌤️ **Weather Impact on Rides**: Categorized days into **Favorable** and **Unfavorable**
- ⏱️ **Ride Duration Distribution** by time buckets

---

## 🛠️ Tools & Technologies

- **Power BI** – For dashboard design, data modeling, and DAX calculations
- **Python (Pandas)** – For data cleaning, merging, and weather condition classification
- **Power Query (M)** – For transforming and loading data
- **Git** – For version control

---

## 📁 Data Sources

- **[BIXI Montréal Trip Data (2024-H1 Sample)](https://www.bixi.com/en/open-data)**  
  Provided ride-level data including start/end time, station names, and geolocation.

- **[Government of Canada Historical Weather Data](https://climate.weather.gc.ca/)**  
  Metrics like snow on the ground, wind speed, and total precipitation were used to classify days.


## 🧪 Python Data Processing Highlights

- Combined and cleaned trip datasets (start/end stations, timestamps)
- Removed station duplicates and created dimension tables `dim_station`
- Generated custom weather labels (Favorable / Unfavorable)
- Removed nulls and anomalies before exporting to Power BI

---

## 🧠 Key Takeaways

- Built a compelling visual narrative on how weather significantly affects ridership.

- Applied advanced DAX measures and interactive slicers for custom filtering.

- Improved UX by simplifying visuals and highlighting the most actionable insights.

- This project demonstrates end-to-end data analysis, visualization, and storytelling skills.

---

![image](https://github.com/user-attachments/assets/34a99855-84fb-4932-aaf0-6a5e4993b307)
