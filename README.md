# 2026 MSc Dissertation Project

## Project Title

**Forecasting Energy Market Risk Using Demand, Renewable Generation and Gas Market Indicators**

## Project Overview

This repository contains the code, data structure, outputs and project notes for my MSc Data Analytics dissertation.

The project focuses on forecasting energy market risk using publicly available energy market data. It explores how electricity demand, renewable generation, carbon intensity and selected gas market indicators can be used to identify and forecast periods of elevated energy market risk.

The dissertation falls under the **time-series forecasting** category and will compare suitable statistical and machine-learning approaches.

## Aim

The aim of this project is to develop a data-driven forecasting framework for identifying periods of elevated energy market risk using demand, renewable generation, carbon intensity and gas market indicator data.

## Research Questions

1. How do demand, renewable generation, carbon intensity and gas market indicators vary over time?
2. Can time-series and machine-learning models be used to forecast periods of elevated energy market risk?
3. Which variables are most useful in explaining or predicting elevated energy market risk?
4. What are the commercial implications of the findings for energy analytics, revenue assurance and market decision-making?

## Objectives

* Collect and organise publicly available energy market datasets.
* Clean and prepare the data for time-series analysis.
* Explore trends, seasonality and relationships between demand, renewable generation, carbon intensity and gas indicators.
* Define a practical measure of elevated energy market risk.
* Build and compare appropriate forecasting models.
* Evaluate model performance using suitable forecasting metrics.
* Interpret the results in relation to commercial energy analytics and revenue assurance.

## Data Sources Reviewed

The initial data source review has considered the following publicly available datasets:

* **NESO Historic Demand Data 2023**: electricity demand, wind generation and solar generation.
* **Carbon Intensity API 2023**: forecast carbon intensity, actual carbon intensity and carbon intensity index.
* **ONS System Average Price of Gas 2023**: daily System Average Price of gas and seven-day rolling average.

These datasets will be used to support the construction of a wider energy market risk dataset. Further cleaning, alignment and integration will be completed in later stages of the project.

## Proposed Methodology

The project will follow a structured data analytics workflow:

1. Data collection
2. Data cleaning and preprocessing
3. Data integration
4. Exploratory data analysis
5. Feature engineering
6. Time-series forecasting
7. Model comparison
8. Evaluation of forecasting performance
9. Commercial interpretation of results

Potential modelling approaches may include baseline forecasting, ARIMA/SARIMA, regression-based forecasting and machine-learning models such as Random Forest or Gradient Boosting.

## Repository Structure

```text
2026-MSc-Dissertation-Project/
│
├── Data/
│   ├── raw/              # Original downloaded datasets
│   └── processed/        # Cleaned and processed datasets
│
├── Notebooks/            # Jupyter notebooks for data review, analysis and modelling
│
├── Outputs/
│   ├── figures/          # Saved charts and visual outputs
│   └── tables/           # Saved summary tables and review outputs
│
└── README.md             # Project overview and repository guide
```

## Current Status

The project is currently in the initial data review stage. The project structure has been created, the GitHub repository has been set up, and the first data source review notebook has been developed.

The datasets reviewed so far include NESO Historic Demand Data, Carbon Intensity API data and ONS System Average Price of Gas data. Initial checks have been completed for file structure, date coverage, frequency, missing values and suitability for the dissertation.

The next stage will focus on cleaning, aligning and integrating the selected datasets into a combined time-series dataset for exploratory analysis and modelling.

## Author

**Oluwatosin Jimoh**
MSc Data Analytics, Part-time
Queen Mary University of London
