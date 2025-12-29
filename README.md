# Grocery Sales Demand Forecasting

## Objective
The objective of this project is to forecast daily sales demand at the
store and product category level and to identify key factors
(e.g., price, discounts, loyalty programs) that influence sales performance.

## Dataset
- name: Grocery Store Sales Dataset in 2025 - 1900+ Record
- Period: Aug 2023 – Aug 2025
- License: Apache License 2.0
- Records: 1,980 rows
- Source: https://www.kaggle.com/datasets/pratyushpuri/grocery-store-sales-dataset-in-2025-1900-record

## Current Status
- Initial EDA completed
- Identified an appropriate aggregation level (day × store × product category)
- Performed feature engineering based on aggregated data
- Finalized candidate target variable (final_amount)
- Feature set is ready; modeling will start next

## Modeling Plan
Tree-based models (e.g., Decision Tree, Random Forest) will be used as
baseline models for demand forecasting.
