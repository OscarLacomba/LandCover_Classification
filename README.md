# Land Cover Classification - MODIS Lake Powell

Remote sensing land cover classification using MODIS satellite data from Lake Powell.

## Overview
This project walks through the full data science lifecycle to classify water and land cover features from remote sensing data.

## Steps
1. Import libraries
2. Load dataset from HuggingFace
3. Exploratory Data Analysis (5 visualizations)
4. Feature Engineering (NDVI, NDWI, MNDWI, statistical aggregates)
5. Train/Test split
6. Model training (Random Forest, XGBoost, LightGBM)
7. Predictions and evaluation
8. Explainable AI - SHAP feature importance

## Dataset
[NASA CISTO - MODIS Lake Powell Toy Dataset](https://huggingface.co/datasets/nasa-cisto-data-science-group/modis-lake-powell-toy-dataset)

## HuggingFace Space
[Live Demo](https://huggingface.co/spaces/osky9/Land_Cover_classification)

## Tech Stack
- Python, Streamlit
- scikit-learn, XGBoost, LightGBM
- SHAP, matplotlib, seaborn, plotly
