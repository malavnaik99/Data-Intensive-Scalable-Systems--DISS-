# Data Intensive Scalable Systems (DISS)


# 📊 Trend of Global Energy Demand for Electric Vehicles: A Distributed Computing Approach


## 🧠 Abstract

This project presents a scalable, cloud-based data pipeline for analyzing and predicting global energy demand from electric vehicles (EVs). Leveraging **Apache Spark** and **Azure Databricks** alongside **PostgreSQL**, the system processes over **1 million EV records** to extract patterns in electricity usage across different vehicle and charger types. Forecasting is enhanced using advanced statistical and machine learning models. The study highlights that four-wheelers consume 58% more energy than two-wheelers, and DC chargers use twice the energy of AC chargers.

---

## 📌 Objectives

- Develop a distributed computing architecture for processing large-scale EV datasets.
- Identify key determinants of EV energy consumption based on vehicle type and region.
- Forecast short- and long-term global EV energy demands.
- Provide actionable insights for policymakers, utility companies, and urban planners.

---

## ❓ Research Questions

1. What methodologies are most effective for forecasting EV energy demand?
2. How do vehicle specifications impact energy consumption?
3. What are the regional variations in EV usage and infrastructure needs?

---

## 🗃️ Dataset

- **Source**: [Mme-Box/vehicles](https://huggingface.co/datasets/Mme-Box/vehicles) (Hugging Face)
- **Volume**: 1+ million EV records
- **Features**: Battery capacity, vehicle type, energy consumption, CO₂ emissions, charger type, and regional metadata

---

## 🔧 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **Azure Databricks** | Distributed data processing with PySpark |
| **Apache Spark** | Parallel data transformation and analysis |
| **PostgreSQL + TimescaleDB** | Time-series data storage and querying |
| **Python** | Data analysis and machine learning |
| **LSTM Networks** | Future trend prediction |
| **Matplotlib / Seaborn** | Data visualization |

---

## 🛠️ Architecture Overview

```
Data Ingestion (Azure Data Factory)
            ↓
Distributed Processing (Azure Databricks + PySpark)
            ↓
    Feature Engineering & Transformation
            ↓
Storage (Azure PostgreSQL with TimescaleDB)
            ↓
      ML/DL Modeling & Visualization
```

---

## 📈 Key Results

- **EV Growth**: Global EV count increased 4.75x from 2019 to 2021.
- **Energy Forecast**: Projected demand rises from 120 TWh (2019) to 3,300 TWh (2050).
- **Consumption Patterns**:
  - EVs are 85–90% efficient and emit zero tailpipe CO₂.
  - Petrol/Diesel vehicles show >200% higher energy consumption.
  - DC charging stations demand 2x energy compared to AC.

---

## 🔍 Insights & Implications

- **Grid Planning**: Peak-hour energy loads must be anticipated.
- **Policy Framing**: Data-driven subsidy and regulation planning.
- **Sustainability**: Aligns with renewable integration goals for a zero-emission future.

---

## 🧪 Future Work

- Integrate **real-time data feeds** and **vehicle-to-grid (V2G)** prediction.
- Extend model to support **scenario-based simulation** for policy planning.
- Incorporate **geospatial visualizations** for region-specific insights.

---

## 📄 Report

The full technical report and findings are available in the [`25709_Malav_Hiteshbhai_Naik_malav_x23271779_60835_1371866095.pdf`](./25709_Malav_Hiteshbhai_Naik_malav_x23271779_60835_1371866095.pdf) file.

