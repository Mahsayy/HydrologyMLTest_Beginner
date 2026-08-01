# Rainfall-Runoff Prediction Using Machine Learning

## Overview

This project explores the application of machine learning algorithms for rainfall-runoff prediction. The main objective of this work was to develop a simple introductory workflow to understand the fundamental concepts of applying machine learning techniques in hydrological modeling.

Using rainfall observations from a single meteorological station, machine learning models were trained to predict streamflow responses. This project was developed as a learning exercise to gain practical experience with data preprocessing, model training, evaluation, and interpretation of machine learning results in hydrology.

---

## Objectives

The main objectives of this project were:

* Understanding the workflow of machine learning applications in hydrological problems
* Exploring the relationship between precipitation and runoff response
* Implementing tree-based machine learning algorithms for streamflow prediction
* Learning the basic concepts of model training and performance evaluation

---

## Methodology

The workflow of this project includes:

1. **Data Collection**

   Historical rainfall data from a meteorological station were used as input variables, while observed streamflow data were considered as the prediction target.

2. **Data Preprocessing**

   * Data cleaning
   * Handling missing values
   * Preparing input and output datasets
   * Splitting data into training and testing sets

3. **Machine Learning Models**

   Two tree-based regression algorithms were implemented:

   * **Random Forest (RF)**
   * **Extreme Gradient Boosting (XGBoost)**

4. **Model Evaluation**

   The model performances were evaluated using common regression metrics:

   * Root Mean Square Error (RMSE)
   * Mean Absolute Error (MAE)
   * Coefficient of Determination (R²)

---

## Workflow

```
Rainfall Data
      |
      ↓
Data Preprocessing
      |
      ↓
Machine Learning Models
      |
      ├── Random Forest
      |
      └── XGBoost
      |
      ↓
Streamflow Prediction
      |
      ↓
Model Evaluation
```


## Author

Mahsa Younesi

Background: Water Resources Engineering | Hydrological Modeling | Machine Learning Applications

---

## Disclaimer

This project was developed as an introductory machine learning exercise to understand the basic workflow of applying data-driven methods in hydrology.
