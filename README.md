# 🌡️ Tamil Nadu Climate Change & Urban Heat Island Analysis (2000–2023)

This repository presents a comprehensive analysis of temperature patterns in Tamil Nadu from 2000 to 2023. It investigates climate change signals at the district level and the intensity of urban heat island (UHI) effects across seasons and regions using satellite-derived temperature data and geospatial tools.

---

## 📥 Data Sources

- **NASA POWER API**: Daily gridded temperature data (converted to district-level monthly averages)
- **District Shapefile**: Geospatial boundaries for mapping and regional grouping
- **Urban-Rural Classification**: District-level tagging using external administrative metadata

---

## 🧹 Data Cleaning & Preparation

- Extracted and converted NASA POWER data into district-month format using coordinate mapping
- Merged temperature data with district shapefiles via GeoPandas
- Classified data into Urban and Rural categories
- Removed nulls, ensured uniform date formatting, and filtered valid temperature records

---

## 🧪 Methodology

### 🔬 Statistical Analyses
- **T-Test**: Assessed statistical significance of Urban vs Rural temperature differences
- **Mann-Kendall Trend Test**: Detected long-term monotonic warming trends

### 📊 Visual Analyses
- **Heatmaps**: Monthly UHI anomalies (Urban – Rural)
- **Choropleth Maps**: Summer and winter temperature distribution by district
- **Heatwave Frequency Maps**: Number of months with temperatures >35°C per district

---

## 🔍 Key Insights

- **Statistically Significant Urban-Rural Differences**: Urban areas are slightly cooler on average, but differences are significant (p < 0.01), hinting at potential data source or geographic sampling effects.
- **Strong Climate Trends**: 7 districts (e.g., Thoothukudi, Virudhunagar) showed significant increasing temperature trends (Mann-Kendall).
- **Hottest Zones**: Thanjavur, Tiruvarur, and Nagapattinam consistently recorded the highest average annual temperatures.
- **Coolest Zones**: The Nilgiris and Theni remained the coolest, benefiting from altitude and vegetation.
- **Heatwave Burden**: Southern districts saw more frequent heatwaves, reinforcing regional climate vulnerability.

---

## 📂 Repository Structure

- `data/`: Raw and cleaned data files
- `plots/`: Saved PNGs of all visual outputs
- `Tamil_Nadu_Temperature.ipynb`: Full annotated analysis notebook
- `README.md`: Project overview and documentation

---

## 👨‍💻 Built With

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, GeoPandas, SciPy, PyMannKendall
- **Geospatial Tools**: Shapefiles, coordinate mapping, district-level joins

---

## 📌 Objective

To provide policymakers, researchers, and the public with an open, interpretable baseline of climate heating and urban thermal stress in Tamil Nadu, enabling evidence-driven adaptation strategies.
