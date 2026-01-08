# Belgrade Air Pollution EDA

## Overview

This project focuses on data preprocessing and exploratory data analysis (EDA) of air pollution data collected from Belgrade, Serbia, covering the period December 2021 to March 2022. The goal is to understand pollutant behavior, identify patterns, correlations, and outliers, and prepare the dataset for potential future data mining tasks.

The analysis was performed using Python.

---

## Dataset

* Records: 81 daily observations
* Pollutants: SO₂, PM10, PM2.5, NO, NO₂, NOx, CO
* Meteorological variables: Temperature (T), Pressure (P), Relative Humidity (RH)
* Location: Belgrade (single city; city column removed during preprocessing)
* The dataset contains no missing values, making it suitable for direct analysis.

---

## Methods Used

### 1. Data Preprocessing

* Dataset loading using pandas
* Dataset inspection (info(), head())
* Removal of redundant city column
* Conversion of time column to datetime
* Generation of descriptive statistics
* Feature scaling using StandardScaler (Z-score normalization)

### 2. Exploratory Data Analysis (EDA)

* Histograms for distribution analysis
* Boxplots for variability and outlier detection
* Correlation heatmap to analyze relationships
* Pairplots for multivariate visualization
* Manual statistical analysis on the first 10 records for comparison

---

## Tools & Technologies

* Python
* pandas
* matplotlib
* seaborn
* sklearn.preprocessing

---

