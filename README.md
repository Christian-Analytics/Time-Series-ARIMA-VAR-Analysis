# 📈 Macroeconomic Forecasting and Causality Analysis 

This repository contains a RATS Econometrics software coding file and supplementary materials for forecasting and causal analysis of selected macroeconomic variables using ARIMA and VAR models.

## Overview

In this project, we analyze the following macroeconomic variables:

- Consumer Confidence Index (Seasonally Adjusted and Normalized) 📈
  - Data Source: [Federal Reserve Economic Data](https://fred.stlouisfed.org/series/CSCICP03USM665S)

- Housing Price Index 🏠
  - Data Source: [Data.gov](https://catalog.data.gov/dataset/fhfa-house-price-indexes-hpis-948c6)

- Federal Funds Rate 💵
  - Data Source: [Federal Reserve Economic Data](https://fred.stlouisfed.org/series/DFF)

- Government Job Openings (Seasonally Adjusted) 🏢
  - Data Source: [Federal Reserve Economic Data](https://fred.stlouisfed.org/series/JTS9000JOL)

The analysis includes using **RATS Econometrics software** to implement ARIMA models for forecasting and VAR models to test for causal relationships among these variables.

## Repository Structure

- `Final Project.rpf`: The main RATS file containing all models and analysis.
- `FinalProjectData.xlsx`: Excel file containing the raw data used in the analysis.
- `Final Project Rats.pdf`: PDF document with primary analysis, including model details and results.

## Key Findings

- ARIMA models were applied to each variable using RATS, and forecasts were generated based on the selected models.
- VAR models were used to test for predictive causality among pairs of variables. Significant causal relationships were identified at the 5% level.
- The analysis highlights the complexities of macroeconomic interactions, showcasing both forecast accuracy and causal inference using rigorous econometric techniques.

## Usage

To replicate the analysis:

1. Clone this repository to your local machine.
2. Open `Final Project.rpf` in RATS to access the complete analysis.
3. Review `Final Project Rats.pdf` for primary analysis and insights.
4. Utilize `FinalProjectData.xlsx` for exploring the raw data used in the study.
