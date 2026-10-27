# Taxi Demand Prediction Using Machine Learning

## Project Overview

This project aims to predict unusually high taxi demand in the next hour for different pickup zones in New York City using machine learning classification models.

The goal is to help identify areas where taxi demand may be high, supporting better vehicle allocation and repositioning decisions.

## Dataset

- **Source:** [NYC Taxi & Limousine Commission — Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Dataset:** January 2025 Yellow Taxi Trip Records
- **Features used:** Pickup datetime and pickup location ID

The original dataset is not included in this repository because of its large file size. Download the January 2025 Yellow Taxi Parquet file from the official source before running the notebook.

## Machine Learning Models

The project compares three classification algorithms:

- Logistic Regression
- Decision Tree
- Random Forest

## Project Workflow

1. Load and clean the taxi trip data.
2. Aggregate trips into hourly pickup-zone demand.
3. Create features and define high-demand labels.
4. Split the data into training and testing sets.
5. Train and evaluate the classification models.
6. Compare model performance and generate predictions.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook
- Matplotlib and Seaborn (if used in the notebook)

## Project Files

- `python taxi_demand.ipynb` — notebook containing the analysis and machine learning workflow.
- `taxi_demand_predictions.csv` — generated predictions, if available.
- `.gitignore` — excludes the original dataset and unnecessary local files.

## Status

This project is being developed as a machine learning classification project. Model performance will be reported after evaluating the trained models.

## Author

Pavithra K M
