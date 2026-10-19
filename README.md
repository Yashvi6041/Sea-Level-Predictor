# Sea-Level-Predictor

## Overview
An end-to-end Machine Learning pipeline designed to forecast global average sea levels using historical data. This project utilizes polynomial feature engineering and Ridge Regression to capture the non-linear, accelerating rate of sea-level rise, providing predictions up to the year 2050.

## Architecture
- **Data Handler**: Manages ingestion and automated mock data generation.
- **Feature Engineer**: Applies polynomial transformations to time-series indices.
- **Predictor**: Utilizes Scikit-Learn's Ridge Regression for robust forecasting.
- **Visualizer**: Generates publication-ready Matplotlib visualizations.
