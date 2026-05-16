# Flight Delay Dataset — 2024

## Overview

This project is a Data Analytics academic project focused on analyzing flight delays, cancellations, airline activity, and flight performance using real-world flight data. The project utilizes Power BI for data visualization and dashboard development.

The website serves as an overview presentation of the project, including the dataset description, data preprocessing, exploratory data analysis, data modeling, dashboard visualization, insights, and recommendations.

The project also applies the CLEAN Framework for data preprocessing and uses a Star Schema model to organize the dataset for efficient analysis and interactive dashboard visualization.

---

# Dataset Information

* **Dataset:** Flight Delay Dataset — 2024
* **Records:** 7M+ flight records
* **Columns:** 35 columns
* **Source:** Kaggle / Bureau of Transportation Statistics (BTS)
* **Format:** CSV

The dataset contains flight-related information such as:

* flight dates
* airline carrier codes
* origin and destination airports
* departure and arrival delays
* cancellation information
* distance
* delay causes

---

# Tools and Technologies Used

* Power BI
* HTML
* CSS
* JavaScript
* Kaggle Dataset

---

# CLEAN Framework Applied

## C — Conceptualize the Data

The grain, key metrics, and dimensions of the dataset were identified before analysis.

## L — Locate Solvable Issues

The dataset was checked for incorrect data types, inconsistent formatting, and minor data issues.

## E — Evaluate Unsolvable Issues

The dataset was evaluated for anomalies and unsolvable issues.

## A — Augment

Additional derived information such as `delay_status` was created to classify flights as Early, On-Time, or Delayed.

## N — Note and Document

Data types and formatting inconsistencies were corrected and documented for analysis consistency.

---

# Data Modeling

The project uses a **Star Schema** data model consisting of:

## Fact Table

* `flight_data_fact`

## Dimension Tables

* `date_dim`
* `airline_dim`
* `origin_airport_dim`
* `destination_airport_dim`

---

# Dashboard Features

The Power BI dashboard includes:

* KPI Cards
* Interactive Filters and Slicers
* Bar Charts
* Line Charts
* Donut Charts
* Delay Trend Analysis
* Airline Activity Comparison
* Delay Cause Analysis
* Forecasting Visualization

---

# Key Metrics

* Total Flights
* Average Arrival Delay
* Delay Rate
* Cancellation Rate
* Average Distance

---

# Insights and Recommendations

The dashboard findings were analyzed to identify:

* high flight activity trends
* monthly delay variations
* common causes of delays
* flight status distribution

Recommendations were provided to improve scheduling, operational monitoring, and delay management.

---

# Academic Purpose

This project was developed for academic and educational purposes as part of a Data Analytics course requirement.
