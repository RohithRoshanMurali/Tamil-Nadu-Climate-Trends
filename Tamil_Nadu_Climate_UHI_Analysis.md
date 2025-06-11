
# Tamil Nadu Climate and Urban Heat Island (UHI) Analysis (2000–2023)

This report summarizes the key findings from an in-depth analysis of long-term climate data across all districts of Tamil Nadu using NASA POWER API-derived temperature records and urban-rural classification.

---

## General Temperature Trends

- **Hottest Districts**:
  - Thanjavur, Tiruvarur, Nagapattinam, Mayiladuthurai, Ramanathapuram
  - Avg. temperatures ≈ 28.2–28.3 °C

- **Coolest Districts**:
  - The Nilgiris, Theni, Coimbatore, Krishnagiri, Vellore
  - Avg. temperatures ≈ 23.5–25.3 °C

- **Hottest Year Overall**:
  - 2019 (Avg. temp: 27.64 °C)

- **Top 5 Monthly Extremes**:
  - Ranipet (May 2003): 33.7 °C
  - Pudukkottai, Karur, Tiruppur, Virudhunagar — all extreme values in April–May

---

## Urban vs Rural Temperature Differences

- **Urban Avg**: 26.69 °C  
- **Rural Avg**: 26.99 °C  
- Slightly **hotter rural temperatures**, likely due to geographic positioning.

- **T-Test Result**:
  - t = -4.48, p ≈ 7.6e-6 → **Statistically significant difference**

---

## Statistically Significant Warming Trends (Mann-Kendall)

| District         | Trend        | Slope (°C/year) | P-value     |
|------------------|--------------|-----------------|-------------|
| Thoothukudi      | Increasing   | 0.060           | 0.0004  |
| Tenkasi          | Increasing   | 0.051           | 0.0013  |
| Virudhunagar     | Increasing   | 0.047           | 0.0106  |
| Kanniyakumari    | Increasing   | 0.046           | 0.0005  |
| Tirunelveli      | Increasing   | 0.046           | 0.0005  |
| Ramanathapuram   | Increasing   | 0.045           | 0.0031  |
| Nagapattinam     | Increasing   | 0.015           | 0.0106  |

Southern districts in the state of Tamil Nadu show **stronger evidence of climate change**.

---

##  UHI (Urban Heat Island) Findings

- **Monthly Urban-Rural Anomaly Heatmap**:
  - Strongest in **March–May**
  - Fluctuations post-2017; highest differences over +1.5 °C observed

- **March & July UHI Trendlines**:
  - Clear anomalies every few years
  - Trendline added with LOWESS smoothing

---

## Spatial Mapping & Seasonal Patterns

- **Summer Avg Temperature Map**:
  - Delta and southern inland districts are hottest

- **Winter Avg Map (Cooler regions = darker)**:
  - Nilgiris and Theni consistently cold

- **Heatwave Frequency Map**:
  - South and delta regions saw most months >35 °C
  - Useful for public health risk identification

---

## Statistical Tests Summary

- **T-Test**: Urban vs Rural temperatures are statistically different
- **ANOVA**: Seasonal variation across districts is significant
- **Mann-Kendall**: 7 districts show confirmed warming trends

---

## Summary

- **Ramanathapuram, Tirunelveli, Thoothukudi, Virudhunagar**: High-risk zones
- **Urban areas show seasonal heating patterns**, though geography influences intensity
- Project combines geospatial mapping, time-series visualization, and statistical inference

---

**Next Steps**:
- Explore humidity and radiation impacts
- Add air quality overlay
- Build interactive dashboard

