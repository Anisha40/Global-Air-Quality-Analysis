# Global Air Quality Analysis: Trends, Hotspots, and PM2.5 Prediction

## Overview
This project analyzes global air quality data to examine pollution patterns across countries and cities, identify high-pollution hotspots, explore temporal trends, segment locations using clustering, and build a baseline model for PM2.5 prediction.

## Objectives
- Explore the distribution of major air pollutants
- Identify cities and countries with higher average PM2.5 levels
- Analyze monthly and seasonal changes in air quality
- Group cities with similar environmental profiles using clustering
- Build a baseline machine learning model to predict PM2.5

## Dataset
The dataset contains air quality and weather-related variables collected across multiple global cities and countries. Key variables include:
- PM2.5
- PM10
- NO2
- SO2
- CO
- O3
- Temperature
- Humidity
- Wind Speed

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Data loading and inspection
2. Data cleaning and preprocessing
3. Feature engineering
4. Exploratory data analysis
5. PM2.5 severity categorization
6. Country and city hotspot analysis
7. Clustering analysis
8. Baseline predictive modeling

## Key Findings
- PM2.5 levels were elevated across many observations in the dataset.
- Some cities showed consistently higher average PM2.5 levels than others.
- Monthly variation was present, but changes across the year were not very strong.
- Correlations between PM2.5 and other variables were weak.
- The baseline prediction model showed limited performance, suggesting that the dataset has weak underlying structure for prediction.

## Methods Used
### Exploratory Data Analysis
The project begins with cleaning the data, checking distributions, and examining pollution levels across cities, countries, and time periods.

### Feature Engineering
Date-based features such as month and season were created to support time-based trend analysis.

### Clustering
K-Means clustering was used to group cities based on pollutant and weather conditions, helping identify similar environmental patterns.

### Predictive Modeling
A Random Forest Regressor was used as a baseline model to predict PM2.5 levels. Feature importance was also reviewed to understand which variables contributed most to the model.

## Limitations
The dataset appears to have limited real-world structure, which affects the strength of the insights and predictive modeling results. Because of this, the project is best interpreted as a demonstration of an end-to-end analytics workflow rather than a source of strong real-world environmental conclusions.

## Files
- `Global_Air_Quality_Analysis_Professional.ipynb` . Main analysis notebook
- `global_air_quality.csv` . Dataset
- `README.md` . Project documentation

## Author
**Anisha Shrestha**
