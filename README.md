# University Rankings Data Analysis 🎓📊

Welcome to the **University Rankings Data Analysis** repository! This project features a comprehensive Python analysis that explores, cleans, and visualizes the **2018–2019 university rankings dataset** sourced from the Center for World University Rankings (CWUR).

## 📝 Overview
This project aims to uncover the primary drivers behind world university rankings. Through rigorous data preprocessing, statistical exploration, and interactive geographic mapping, this notebook demonstrates how metrics such as research output, faculty quality, and influence correlate with the overall university score.

## ✨ Key Features
- **Data Cleaning & Preprocessing**: Handles missing values, standardizes column names (e.g., removing non-breaking spaces), and converts complex string boundaries (`-`, `> 1000`, `< 1000`) into usable numerical float formats.
- **Custom Analytics**: Features a custom `describe()` function that generates an in-depth data quality report, assessing missing values, duplicates, and data floatability for each column.
- **Exploratory Data Analysis (EDA)**: Utilizes correlation matrices, heatmaps, scatter plots, and box plots to identify relationships between individual ranking metrics and the final score.
- **Geocoding & Interactive Visualization**: Leverages `geopy` to find the exact coordinates (latitude and longitude) of universities and maps their global distribution interactively using `Plotly` and Mapbox. Also includes manual fallback coordinate corrections for complete map coverage.

## 🛠️ Technologies & Libraries Used
This project is built using Python within a Jupyter Notebook environment.
* **Data Manipulation**: `pandas`, `numpy`
* **Data Visualization**: `matplotlib`, `seaborn`, `plotly.express`
* **Geocoding & Mapping**: `geopy`

## 📂 Dataset
The dataset used in this project is the **2018–2019 CWUR University Rankings** (located at `src/eighteen_nineteen_university_datasets.csv`). 
It includes fields such as *World Rank, Institution, Location, National Rank, Quality of Education, Alumni Employment, Quality of Faculty, Research Output, Quality Publications, Influence, Citations,* and *Score*.

## 💡 Key Findings
1. **Strong Predictors**: The overall University `Score` exhibits high positive correlations with **Quality of Faculty**, **Research Output**, **Quality Publications**, **Influence**, and **Citations**.
2. **Data Anomalies**: The raw dataset required significant wrangling, proving that rank boundaries and placeholder nulls must be standardized for robust statistical analysis.
3. **Geographic Clustering**: Visualizing the universities globally highlights distinct regional centers of academic excellence, prominently clustered in North America, Western Europe, and East Asia.
4. **Primary Takeaway**: Research quality and faculty excellence consistently emerge as the strongest predictors of overall university ranking performance.

## Let's Connect
* **LinkedIn**: [Let's network!](https://www.linkedin.com/in/mohammad-amin-saeini)
* **Kaggle**: [Check out on Kaggle!](https://www.kaggle.com/code/mohammadaminsaeini/university-rankings-data-analysis)

