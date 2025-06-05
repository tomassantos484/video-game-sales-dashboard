# 🎮 Video Game Sales Dashboard – Looker Studio

This project presents an interactive data visualization dashboard built in Looker Studio using sales data from VGChartz. The goal is to help a global gaming publisher understand trends in video game sales across platforms, genres, regions, publishers, and review scores.

🔗 **Live Dashboard Link**:  
[View the Report on Looker Studio](https://lookerstudio.google.com/reporting/ec5bf369-df97-4436-929d-23642633da2f)

---

## 📊 Dashboards Overview

### 📘 Dashboard 1: Global Sales Overview
- **Top 10 Best-Selling Games** (Bar Chart)
- **Console Sales Share** (Donut Chart)
- **Publishing Trends Over Time** (Line Chart)
- **Highest-Grossing Genres** (Tree Map)
- **Regional Revenue Breakdown** (Scorecards)

### 📙 Dashboard 2: Publisher, Genre, and Review Analysis
- **Publisher Performance** (Avg Sales vs Volume)
- **Critic Score vs Sales** (Bubble Chart by Genre)
- **Genre Popularity by Region** (Stacked Bar Chart)
- **Console Sales Heat Map** (Table with conditional formatting)
- **Top Publishers in Action/Shooter** (Filtered Table)

---

## 💡 Business Insights

### Global Sales Overview
> Global video game sales surged between 2000 and 2010, driven by blockbuster franchises like *Grand Theft Auto* and *Call of Duty*, alongside high-impact consoles such as the PlayStation 2, PlayStation 3, and Xbox 360.

### Publisher, Genre, and Review Analysis
> RedOctane and Rockstar Games lead in average sales per game, while EA Sports dominates in title volume. Action and Shooter genres drive global revenue, especially in North America, though higher critic scores don’t always lead to stronger sales.

---

## 📁 Dataset Setup Instructions

1. Download the dataset from: `vgchartz-2024.csv`
2. Upload to Google Sheets and name it `Video Game Sales 2024`
3. Paste all data into the first tab.
4. Columns must include:
   - `title`, `console`, `genre`, `publisher`, `developer`, `critic_score`, `total_sales`
   - `na_sales`, `jp_sales`, `pal_sales`, `other_sales`
   - `release_date`, `last_update`
5. In Looker Studio, go to **Create → Data Source → Google Sheets**, select your sheet, and connect.

---

## 🛠️ How Did I Make This?
- Google Looker Studio
- Google Sheets as Data Source
- Calculated Fields (e.g., `release_year`, `average_sales_per_publisher`)
- Custom filters and sorting
- Scorecards, Donut/Tree Maps, Heat Maps, and Scatter Plots

---



## 📸 Dashboards In Action


