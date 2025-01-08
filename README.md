# Taxi Demand Prediction and Allocation

## Overview
This project analyzes and predicts taxi demand across Manhattan using data-driven approaches, machine learning models, and geospatial visualizations. It provides actionable insights to optimize taxi allocation and improve transportation planning.

The primary objective is to uncover spatial and temporal patterns in taxi activity, predict future demand using historical data, and design a system for real-time demand allocation and visualization. This repository contains all code, datasets, and documentation for the project.

## Features

1. **Data Preparation**: Cleaning, structuring, and aggregating datasets with temporal and geospatial features.
2. **Machine Learning Models**:
   - Random Forest for initial predictions.
   - Neural Networks (RNN, LSTM, GRU) for sequential data analysis.
3. **Regional Classification**:
   - Segmentation of Manhattan into five regions using QGIS and GeoJSON.
   - Grid-based geospatial analysis for detailed predictions.
4. **Dynamic Allocation**:
   - Probabilistic distribution of demand across regions and cells.
   - Real-time visualization for taxi drivers using interactive maps.
5. **Database Architecture**:
   - Normalized schema for efficient data management.
   - Scalable and flexible design to integrate additional features.

## Technologies Used
- **Programming Languages**: Python, R
- **Libraries**:
  - Data Analysis: pandas, geopandas, numpy
  - Machine Learning: scikit-learn, TensorFlow, PyTorch
  - Visualization: Plotly, Matplotlib, Tableau, Power BI
- **Geospatial Tools**: QGIS, Folium, OpenStreetMap
- **Database**: SQL-based schema design

## Project Structure
```
├── data
│   ├── raw_data           # Raw input datasets
│   ├── processed_data     # Cleaned and structured datasets
├── notebooks              # Jupyter notebooks for exploratory data analysis
├── models
│   ├── random_forest      # Random Forest implementation
│   ├── neural_networks    # RNN, LSTM, GRU models
├── visualizations
│   ├── dashboards         # Power BI and Tableau dashboards
│   ├── maps               # Geospatial visualizations
├── scripts
│   ├── data_processing    # Data cleaning and preprocessing
│   ├── geospatial_analysis # Regional classification and grid creation
│   ├── prediction         # Model training and evaluation
│   ├── allocation         # Dynamic demand allocation scripts
├── database
│   ├── schema.sql         # Database schema design
├── report                 # Project report and documentation
└── README.md
```


## Results
- Detailed performance metrics of machine learning models (Random Forest, RNN, LSTM, GRU).
- Region-specific and grid-based demand predictions.
- Insights on temporal and weather-related patterns.
- Real-time interactive visualization for taxi drivers.

## Report
The project report includes a detailed explanation of the methodology, results, and insights. The report can be accessed [here](https://www.overleaf.com/read/qvcwjmddbxyd#888367).

## Contributors
- Maryana Kamal Kamal Megahed
- Salma Tarek Abdelmonem Salem
- Karim Khaled AbdelAziz Hassan Hosny
- Marina Atef Shaker Wissa
- Omar Mohamed Ahmed Hussein
- Sama Mohamed Mohamed Elkhamry
- Logain Emad Eldin Awad Mahmoud
- Mohamed Akram Mohamed Aly

## Supervisor
- Dr. Islam Ali



