    
# 🎬 Netflix Insights Dashboard – Power BI

**File:** `Powerbi_netflix.pbix`  
**Tool Used:** Power BI Desktop  
**Author:** Pooja VT  
**Purpose:** To explore and visualize Netflix content data including genres, countries, years, cast distribution, and content trends.

---

## 🔍 Overview

This dashboard offers an interactive visualization of Netflix's content library, enabling users to filter and analyze:

- Distribution of content by **genre**, **type**, and **country**
- **Year-wise** content additions to the platform
- **Cast** and **director** network exploration
- Ratings, durations, and regional availability insights

---

## 📈 Key Features

### 1. Content Type & Genre Distribution
- Breakdown of Movies vs TV Shows
- Most common genres, sub-genres

### 2. Country-Level Analysis
- Explore which countries produce the most content available on Netflix
- Supports multi-country per show breakdown

### 3. Time Trend Analysis
- Track how Netflix's content library has grown over the years
- Filter by release year or addition year

### 4. Cast and Crew Insights
- Top appearing actors/actresses
- Interactive visuals to explore relationships

---

## 🛠 Technical Highlights

- **Data Transformation**: Unpivoting and splitting multi-country or multi-cast fields using Power Query
- **Custom Measures**: Using `CALCULATE`, `FILTER`, `DISTINCTCOUNT` for deep metrics
- **Bookmarks & Navigation**: For seamless tab-style navigation

---

## 📤 How to Use

1. Open the `.pbix` file in **Power BI Desktop**
2. Use the slicers to filter by year, genre, country, and cast
3. Click visuals or buttons to navigate between detailed views
4. Hover over graphs for detailed tooltips

---

## 🔄 Future Scope

- Add viewing trends if user watch history data is available
- Predictive content clustering using ML (Python integration)
- Incorporate IMDb/Rotten Tomatoes scores via API

---

## 📌 Notes

- Make sure to refresh data sources if you’ve connected this to external CSVs
- Custom visuals used: Bar chart, Tree map, Card, Table, Line chart

---



    
