# Optimising Advertising Performance Using Predictive Modelling

## Overview

This project develops a data-driven framework to optimise digital advertising placement using predictive modelling and contextual decision policies. The objective is to maximise Expected Conversions per Impression (ECPI), defined as the product of click-through rate (CTR) and conversion rate.

The project integrates data preprocessing, feature engineering, predictive modelling, and an interactive dashboard to support analysis and decision-making.

---

## Repository Structure

* `Raneem_Project.ipynb` – main notebook containing data preprocessing, feature engineering, modelling, and evaluation
* `ads_dashboard.py` – interactive Streamlit dashboard for exploring advertising performance 
* `Dataset_Ads.csv` – dataset used for analysis

---

## How to Run the Project

### 1. Run the Notebook

* Open `Raneem_Project.ipynb`
* Run all cells from top to bottom
* The notebook performs:

  * Data cleaning
  * Feature engineering
  * Model training
  * Model evaluation

### 2. Run the Dashboard

In your terminal, run:

```
streamlit run ads_dashboard.py
```

The dashboard provides:

* ECPI distribution analysis
* Category-based comparisons (placement, topic, etc.)
* Correlation heatmaps
* Interactive filtering across contextual variables

## Models Used

* Ridge Regression (baseline linear model)
* HistGradientBoosting Regressor (non-linear model)
* Random Forest Regressor (comparative model)

## Key Features

* ECPI-based performance metric (CTR × Conversion Rate)
* Automated feature detection and preprocessing
* Contextual recommendation logic for ad placement
* Interactive dashboard for exploratory analysis


