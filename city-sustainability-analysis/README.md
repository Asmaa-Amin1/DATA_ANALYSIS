# 🌍 City Sustainability & Geospatial Data Analysis

A comprehensive data analysis and interactive visualization project exploring global city sustainability metrics, environmental indicators, and geospatial distributions across different continents.

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Dataset Features](#-dataset-features)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Data Visualizations](#-data-visualizations)
- [Key Insights](#-key-insights)
- [Technologies Used](#-technologies-used)
- [Getting Started](#-getting-started)

---

## 🔍 Project Overview
This project investigates the balance between urban growth, environmental impact, and geographic characteristics for **300 global cities**. By leveraging Python data science libraries, we clean, analyze, and visualize multi-dimensional indicators such as CO2 emissions, renewable energy shares, air quality, and traffic congestion.

---

## 📊 Dataset Features
The dataset contains **300 rows and 13 columns**[cite: 2]:

| Column Name | Data Type | Description |
| :--- | :---: | :--- |
| `city` | string | Name identifier of the city (e.g., City_1, City_2)[cite: 2] |
| `country` | string | Country where the city is located[cite: 2] |
| `continent` | string | Continent classification (North America, Asia, Europe, etc.)[cite: 2] |
| `iso_alpha3` | string | 3-letter ISO country code[cite: 2] |
| `latitude` & `longitude` | float | Geospatial coordinates[cite: 2] |
| `population_millions` | float | City population in millions[cite: 2] |
| `avg_temp_c` | float | Average annual temperature in Celsius[cite: 2] |
| `co2_tons_per_capita` | float | CO2 emissions per capita (tons)[cite: 2] |
| `renewable_energy_share` | float | Percentage share of renewable energy[cite: 2] |
| `air_quality_index` | float | Air Quality Index (AQI)[cite: 2] |
| `traffic_congestion_index` | float | Traffic congestion severity index[cite: 2] |
| `is_coastal` | string | Binary indicator (`Yes` / `No`) for coastal locations[cite: 2] |

---

## 🛠️ Exploratory Data Analysis (EDA)
The analysis workflow included:
1. **Data Inspection**: Checked data types, missing values, and dataset dimensions (`300 entries, 13 columns`)[cite: 2].
2. **Statistical Summary**: Generated descriptive statistics (mean, standard deviation, min, max, and percentiles) for numerical features such as population, temperature, and AQI[cite: 2].
3. **Data Filtering & Grouping**: Examined environmental indicators segmented by continents and geographical features.

---

## 📈 Data Visualizations
Interactive visualizations were created using **Plotly Express** to uncover hidden patterns:
* **Scatter Plot**: Analyzed the relationship between `co2_tons_per_capita` (X-axis) and `air_quality_index` (Y-axis), scaled by `population_millions` and colored by `continent`[cite: 2].
* **Hover Data**: Integrated custom tooltips to show coastal status (`is_coastal`) and average temperatures (`avg_temp_c`) directly on data points[cite: 2].

---

## 💡 Key Insights
* **Emissions vs. Air Quality**: Highlighted variations in per capita carbon footprints across different continental clusters.
* **Population Impact**: Bubble size scaling reveals how major population centers correlate with traffic congestion and resource consumption indices.
* **Geographical Distribution**: Evaluated the environmental profiles of coastal versus inland cities.

---

## ⚙️ Technologies Used
* **Python 3.x**[cite: 2]
* **Pandas**: Data manipulation and cleaning[cite: 2]
* **Plotly Express**: Interactive data visualization[cite: 2]

---

## 🚀 Getting Started

To run this notebook locally, make sure you have the required libraries installed:

```bash
pip install pandas plotly
