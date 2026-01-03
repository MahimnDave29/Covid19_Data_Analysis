# COVID-19 Data Analysis

## Project Overview
This project provides a comprehensive analysis of the COVID-19 pandemic using global data. The notebook explores the spread, evolution, and impact of the virus across different countries and continents. 
The analysis includes exploratory data analysis (EDA), geospatial mapping, trend evaluation over time, and preparation for dynamic visualizations like Bar Chart Races.

## Data Source
The data is sourced directly from **Our World in Data (OWID)**.
- **GitHub:**: https://github.com/owid/covid-19-data
- **Source:** `https://catalog.ourworldindata.org/garden/covid/latest/compact/compact.csv`

## Key Features & Analysis
The notebook is structured into the following key sections:

1.  **Data Loading & Preprocessing**:
    - Automated fetching of the latest dataset.
    - Date parsing and handling of missing values.
    - Filtering global vs. country-specific data.
2.  **Exploratory Data Analysis (EDA)**:
    - Summary statistics of recent information.
    - Creation of summary tables for quick insights.
    - Country-specific deep dives.
3.  **Geospatial Visualization**:
    - Mapping COVID-19 spread across the globe to identify hotspots.
    <img width="1540" height="563" alt="image" src="https://github.com/user-attachments/assets/bee02df8-0df7-477b-ad77-c3e3a8d0243b" />
    <img width="1545" height="563" alt="image" src="https://github.com/user-attachments/assets/608e6099-094b-460d-ae50-33720b310077" />
    <img width="1645" height="630" alt="image" src="https://github.com/user-attachments/assets/71ef6312-82b9-4057-a384-d83329621131" />

4.  **Temporal Evolution**:
    - Analyzing the evolution of cases over time.
    <img width="1550" height="643" alt="image" src="https://github.com/user-attachments/assets/ed730734-f2d9-45f1-8d15-5fd449718527" />
    <img width="1539" height="626" alt="image" src="https://github.com/user-attachments/assets/52cbe523-570e-43db-8247-6373770780e0" />
    <img width="1535" height="629" alt="image" src="https://github.com/user-attachments/assets/37ea95e7-42d2-4d69-9a6f-900c8d2bfd96" />

5.  **Comparative Analysis**:
    - Comparing metrics between different countries and continents.
    <img width="1607" height="545" alt="image" src="https://github.com/user-attachments/assets/ee16d4a5-8c91-4241-82f8-d33712e8fd02" />
6.  **Visualization Export**:
    - Formatting and processing data for external visualization tools (e.g., Flourish Bar Chart Race).
    <img width="1846" height="890" alt="image" src="https://github.com/user-attachments/assets/e900ccad-1362-444b-957c-c9248e43afe8" />

## Libraries used:

- **Pandas**: For data manipulation and ingestion.
- **NumPy**: For numerical operations.
- **Matplotlib**: For static plotting and statistical graphics.
- **Plotly**: For interactive visualizations and maps.
- **Datetime**: For time-series handling.


