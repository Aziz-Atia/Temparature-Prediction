
# Tempurature Prediction in London

## How to run the project:
For running the ipynb file, using colab would be enough.

A machine learning pipeline to predict mean temperatures in London using MLflow for experiment tracking.

## Project Overview
This project builds and evaluates multiple regression models to predict mean daily temperatures in London, England. It features:
- Extensive experiment tracking using MLflow
- Multiple regression models comparison
- Target RMSE of 3°C or less
- Comprehensive weather data analysis

## Dataset
The project uses `london_weather.csv` containing daily weather measurements:
- date: Recording date
- cloud_cover: Cloud cover (oktas)
- sunshine: Sunshine duration (hrs)
- global_radiation: Irradiance (W/m²)
- max_temp: Maximum temperature (°C)
- mean_temp: Target variable - Mean temperature (°C)
- min_temp: Minimum temperature (°C)
- precipitation: Rainfall (mm)
- pressure: Atmospheric pressure (Pa)
- snow_depth: Snow depth (cm)
