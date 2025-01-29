# Advanced Crime Analysis and Visualization

## Overview
This project integrates **PostgreSQL, MongoDB, and Dagster** to perform **advanced crime data analysis and visualization** from multiple structured and semi-structured sources. Our approach combines **data engineering, statistical modeling, and machine learning techniques** to uncover **trends, regional disparities, detection rates, and crime clustering patterns** over two decades **(2003–2023)**.

---

## Key Components

### 1. Database Setup and Data Integration
#### 📌 PostgreSQL & MongoDB Setup:
- Establishes and configures **PostgreSQL** and **MongoDB** databases, ensuring optimized storage and retrieval of **structured and unstructured crime data**.
- Performs **integrity checks** to verify data consistency across databases.

#### 📥 Data Ingestion:
- Loads **historical crime data (2003–2019) into PostgreSQL** and **recent crime data (2018–2023) into MongoDB**.
- Standardizes data across sources using **category mapping, normalization, and structured format transformation**.

---

### 2. Data Processing and Transformation
#### ⚙️ Dagster Pipelines for ETL:
- Utilizes **Dagster assets** to **extract, transform, and load (ETL)** crime data efficiently.
- Transforms raw **crime data into structured** `processed_crime_data` **tables**.

#### 🔄 Data Normalization and Mapping:
- Maps **regional codes from MongoDB to PostgreSQL**, ensuring seamless analysis.
- Unifies **crime categories** across databases using **standard encoding schemes**.

---

### 3. Advanced Crime Data Analysis
#### 📊 Trend Analysis (2003–2023):
- Calculates **yearly crime trend variations** using historical vs. recent data.
- Analyzes **temporal shifts** in crime rates, **detection percentages**, and **severity trends**.

#### 🌍 Regional and Crime Type Comparisons:
- Computes **detection rates by year, region, and crime type** to evaluate **law enforcement efficiency**.
- Examines **prevalent crime types** and **shifts in frequency** over time.

#### 🔍 Crime Pattern Recognition (Clustering & Spatial Analysis):
- Applies **K-Means clustering** to **identify crime hotspots** and behavioral patterns.
- Uses **spatial visualization** techniques to **analyze crime distribution across regions**.

---

### 4. Data Visualization and Dashboards
#### 📈 Trend and Comparison Plots:
- Generates **interactive dashboards** displaying **historical and regional crime trends**.
- Visualizes **top crime categories, detection success rates, and regional distributions** using **Matplotlib and Plotly**.

#### 📉 Crime Detection Rate Analysis:
- Computes **confidence intervals for crime detection vs. non-detection rates**.
- Presents findings through **yearly crime incidence heatmaps** and **detection progress charts**.

---

### 5. Interactive Insights & Future Enhancements
#### 🤖 Machine Learning Extensions:
- Future work includes integrating **predictive analytics** using time-series forecasting (e.g., **ARIMA, LSTM**).

#### 📢 Crime Forecasting & Law Enforcement Impact Assessment:
- Analyzing how **social policies and law enforcement changes** impact **long-term crime rates**.

#### 🗺️ Geospatial Mapping of Criminal Activities:
- Using **GIS tools** to create **heatmaps of crime incidents by area**.

---

## Conclusion
This project delivers **cutting-edge crime data analysis**, bridging **structured SQL data** with **semi-structured NoSQL sources**.  
Through **Dagster-based ETL pipelines, predictive modeling, and dynamic visualization**, we extract **valuable actionable insights** into **crime patterns, law enforcement effectiveness, and public safety strategies**.
