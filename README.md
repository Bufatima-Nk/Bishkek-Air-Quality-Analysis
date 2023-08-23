# Time Series Analysis of Air Quality in Bishkek using AR Model

![Bishkek Air Quality](pm2.5%20range.png)

## Introduction

Welcome to the "Time Series Analysis of Air Quality in Bishkek" repository! This project aims to explore air quality patterns in Bishkek, Kyrgyzstan, using time series analysis techniques. The primary objective is to gain insights into the city's air pollution levels, particularly during the winter months, and provide data-driven recommendations for improving air quality.

## Problem Statement

Bishkek, like many cities worldwide, faces air quality challenges with significant health and environmental impacts. The winter season is of particular concern due to heightened pollution levels attributed to indoor heating activities, fireplace usage, and central heaters. This project aims to quantify the severity of air pollution during these months and shed light on potential causes and solutions.

## Dataset

The analysis relies on a comprehensive dataset covering the period from March 9th, 2019, to May 28th, 2020. With over 10,000 data points, this dataset offers a robust representation of air quality fluctuations in Bishkek. The data includes measurements of particulate matter (PM2.5), a critical indicator of air pollution.

## Approach

### Data Preparation

The analysis starts with essential data preparation steps. Raw data is transformed into a structured format, with timestamps localized for accurate time-based analysis. Outliers are identified and removed, followed by resampling the data to hourly intervals. Missing values are addressed using a forward-fill strategy.

### Exploration and Visualization

Visualizations play a pivotal role in uncovering data patterns. The analysis examines trends in PM2.5 levels over time, identifying temporal variations. Seasonal decomposition is employed to reveal underlying patterns such as trends, seasonal components, and residuals.

### Seasonal Analysis

Seasonal patterns emerge, highlighting the connection between pollution levels and different seasons. Special attention is given to the winter months, characterized by elevated pollution due to increased indoor heating. Box plots and histograms vividly portray the distribution of PM2.5 levels across seasons.

### Autoregressive (AR) Model

An Autoregressive (AR) model is developed to predict future PM2.5 levels based on historical data. The model's performance is evaluated using metrics such as mean absolute error (MAE), providing insights into its predictive capabilities.

### Walk-Forward Validation

To simulate real-world conditions, walk-forward validation is employed. This approach continually updates the model using new observations, mimicking performance over time. The test mean absolute error (MAE) serves as a valuable benchmark for the model's accuracy.

## Key Insights and Findings

The analysis yields essential insights:

- Bishkek experiences severe air pollution, especially during winter.
- The highest recorded PM2.5 value during winter reached a hazardous level of 753.
- Seasonal decomposition reveals distinct pollution patterns across seasons.
- Autoregressive modeling enhances predictive capabilities for PM2.5 levels.
- Walk-forward validation provides a more accurate evaluation of model performance over time.

## Call to Action

The findings underscore the urgency of addressing air pollution in Bishkek, particularly during winter. Improved indoor heating practices and pollution control measures can contribute to a healthier and cleaner environment for the city's residents.

## Contact Information

- **Name:** Bufatima N.k.
- **Email:** bufatima.nk@gmail.com

Feel free to explore the Jupyter Notebook and related files for a deeper dive into the analysis. Your contributions, feedback, and suggestions are highly valued as we work towards a cleaner and healthier Bishkek.

