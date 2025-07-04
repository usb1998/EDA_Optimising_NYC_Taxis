# 🗽 NYC Yellow Taxi Trip Data – Exploratory Data Analysis

## 📌 Project Overview

This project involves Exploratory Data Analysis (EDA) of the 2023 NYC Yellow Taxi trip dataset provided by the NYC Taxi and Limousine Commission (TLC). The objective is to uncover patterns and operational inefficiencies in taxi rides to optimize dispatching, routing, and pricing strategies.

> ✅ **Goal:** Provide data-driven insights to help a new taxi service in NYC enhance efficiency, reduce idle time, and increase revenue while remaining competitive.

---

## 📂 Dataset

- **Source:** [NYC Taxi & Limousine Commission](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Format:** Parquet files (one per month)
- **Size:** 12 files for the year 2023 (~200 million+ records before sampling)

**Fields include:**
- Pickup/dropoff datetime and location
- Trip distance and duration
- Fare, tip, taxes, surcharges
- Passenger count, payment type, rate code

---

## 🔧 Key Tasks Performed

### 🗃️ 1. Data Sampling & Loading
- Sampled 5% of records per hour per day to ensure representative time-based trends.
- Merged 12 monthly files into a single DataFrame (~1.89M rows).

### 🧹 2. Data Cleaning
- Handled missing values (e.g., `passenger_count`, `RatecodeID`).
- Removed or fixed outliers (e.g., `trip_distance = 0` with high fare).
- Combined duplicate columns (`airport_fee`, `Airport_fee`).

### 📊 3. Exploratory Data Analysis (EDA)
- Time-based trends (hourly, daily, monthly analysis)
- Zone-based pickup/dropoff hotspots
- Fare vs distance vs tip relationships
- Analysis of payment types, rate codes, and passenger counts

---

## 💡 Key Insights

- **Peak Demand:** Morning (7–10 AM) and Evening (5–8 PM)
- **High-Demand Zones:** Midtown Manhattan, Airports (JFK, LaGuardia), Financial District
- **Most Trips:** Involve 1–2 passengers, paid by credit card
- **Outliers:** Numerous zero-distance trips with abnormally high fares

---

## 🚕 Recommendations

### 🔁 Routing & Dispatch Optimization
- Increase cab availability in peak hours and zones
- Position idle taxis in demand-heavy micro-clusters
- Use live heatmaps for dynamic rebalancing

### 📍 Strategic Cab Positioning
- Deploy taxis differently on weekdays vs weekends
- Assign more cabs near airports during holidays
- Maintain night coverage in hospitals, transport hubs

### 💰 Pricing Strategy Adjustments
- Introduce dynamic pricing based on demand and congestion
- Offer digital payment rewards and subscription plans
- Set minimum fares for short trips and cap long-trip fares

---

## 🧠 Tools & Technologies

- **Language:** Python
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook
- **Data Format:** `.parquet`, `.csv`

---


