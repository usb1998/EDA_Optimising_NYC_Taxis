# 🚕 EDA – Optimising NYC Taxi Operations

## 🎯 Objective
This project aims to explore, visualize, and derive actionable insights from the New York City taxi trip dataset using **Exploratory Data Analysis (EDA)** techniques. The goal is to identify key patterns, anomalies, and operational opportunities that can help optimize taxi operations across time, location, and fare behavior.

---

## 📦 ZIP Archive

All final files are included in:  
> **`EDA_Optimising_NYC_Taxis_Umair_Birajdar.zip`**

| File Name                                      | Description |
|-----------------------------------------------|-------------|
| `EDA_NYC_Taxi_Analysis.ipynb`                 | Jupyter Notebook containing complete EDA, visualizations, and summary insights. |
| `EDA_Report_NYC_Taxis.pdf`                    | PDF report formatted for business stakeholders. |
| `README.md`                                   | This file – project overview, structure, and findings. |

*Note: The original starter notebook and base files are from the ZIP `Starter-Notebook-EDA-NYC-Taxi.zip`.*

---

## ⚙️ How to Run This Project

1. Unzip the archive: `EDA_Optimising_NYC_Taxis_Umair_Birajdar.zip`
2. Open the `.ipynb` file using:
   - Jupyter Notebook (Anaconda)
   - Google Colab
   - VS Code with Jupyter extension
3. Run cells in order to reproduce the EDA process and visual outputs.
4. Dataset may either be embedded or loaded from CSV depending on notebook setup.

---

## 🔍 Key Exploratory Areas

- Trip duration and distance analysis
- Passenger count distribution
- Time-based patterns (hour, weekday, month)
- Pickup and drop-off location trends
- Fare amount and tip analysis
- Correlations and outlier detection
- Mapping hot zones using latitude-longitude coordinates

---

## 📊 Key Findings

- 🕐 **Trip Duration Trends**: Majority of trips are under 15 minutes, but a few extreme outliers exist.
- 🌇 **Rush Hour Peaks**: Clear spikes in trip volume during weekday mornings and evenings.
- 📍 **Location Hotspots**: Manhattan dominates as the most active pickup and drop-off region.
- 💵 **Fare Behavior**: Fare does not increase linearly with trip distance – suggesting pricing inefficiencies or flat rates.
- 🧍‍♂️ **Passenger Count**: Most trips involve 1–2 passengers; very few have more than 4.
- 🧭 **Geospatial Gaps**: Outlier coordinates indicate incorrect or missing GPS data.

---

## 💡 Recommendations

1. **Clean GPS data** to remove faulty coordinates and enhance spatial accuracy.
2. **Review pricing model** to ensure fairness across short and long trips.
3. **Introduce pooling incentives** for high-density passenger locations.
4. **Add surge pricing caps** during peak hours to maintain ridership affordability.
5. **Target app optimizations** in boroughs with inconsistent pickup patterns.

---

## 🧰 Tools & Libraries

- **Python 3.x**
- pandas, numpy, matplotlib, seaborn, plotly
- folium (for geospatial mapping)
- Jupyter Notebook / Google Colab

---

## 👤 Author Info

**Name**: Umair Birajdar  
**Submission Date**: June 2025  
**Program**: Executive Diploma in Data Science & AI – IIIT Bangalore / upGrad  
**Module**: EDA – NYC Taxi Optimization

---

## 📄 Disclaimer

This is a student project submitted as part of the upGrad curriculum. All analysis is educational and based on publicly available or assigned datasets.
