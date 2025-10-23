# 🚗 Understanding Uber Ride Cancellations in India  

### 📊 A Data Visualization and Analytics Project  
**Author:** Jasmine Kwok  
**Date:** October 2025  

---

## 🧠 Overview  
This project explores **Uber ride cancellations across India** using real-world trip data from Kaggle.  
The analysis identifies **when**, **where**, and **why** rides are most likely to be canceled, uncovering operational patterns and customer behavior insights.  

📦 **Dataset:** [Uber Rides Data (India) – Kaggle]([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard/data))  

---

## 🎯 Objectives  
- Analyze cancellation trends across **time**, **region**, and **vehicle tiers**  
- Identify **high-risk periods** and **hotspot regions**  
- Communicate findings through **visually compelling infographics**

---

## 🧩 Key Insights  
- 🚨 **1 in every 4 rides** in India gets canceled throughout 2024 (~25% cancellation rate)  
- 🌙 Cancellations peak between **3 AM – 6 AM**, especially on **Monday, Thursdays, and Sundays** 
- 🏙️ **Delhi-NCR** is the largest cancellation hotspot, reflecting congestion and demand density
- 🚘 **Budget and Economy tiers** have the highest cancellation rates, often **driver-initiated**

---

## 🧰 Tools & Technologies  
- **Language:** R  
- **Core Libraries:**  
  - `dplyr`, `scales`, `slider` – data cleaning, aggregation, smoothing  
  - `ggplot2`, `ggtext`, `patchwork` – visualization and infographic design  
  - `tidyquant`, `ggseas`, `gghighlight` – trend analysis and time-series smoothing  
  - `ggmap`, `tidygeocoder`, `sf` – spatial data and mapping  
  - `tidyverse` – integrated data wrangling and plotting framework  

---

## 📈 Visualizations  
1. **📅 Time-Series Trend** – 31-day moving average showing cancellation rates steady at ~25% through 2024  
2. **🕒 Heatmap** – Late-night (3 AM – 6 AM) cancellation peaks by day of week  
3. **🗺️ Geographic Hotspot Map with Inset** – Concentration in **Delhi-NCR** region  
4. **🚘 Stacked Bar Chart** – Breakdown by **vehicle tier** and **booking status** 
