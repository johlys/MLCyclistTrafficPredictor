# Predicting Bicycle Traffic in Bergen

This repository contains a data science project aimed at predicting the number of cyclists crossing the Nygård bridge using machine learning. The project is structured into two main Jupyter notebooks and is supported by raw data and generated files.

## Repository Structure
- `raw_data/`: Folder containing the CSV files used for the analysis.
- `data_preparation.ipynb`: Notebook for data preparation and exploratory analysis.
- `data-modeling.ipynb`: Notebook for the modeling phase of the project.
- Generated files from the notebooks (e.g., CSV files for training, validation, and predictions).

## Notebooks Overview

### `data-preparation.ipynb`
This notebook focuses on preparing and exploring the dataset. Key steps include:
- Loading and cleaning traffic and weather data.
- Visualizing various aspects such as monthly traffic patterns and correlations between traffic and weather conditions.
- Splitting the data into training, validation, and test sets.

### `data-modeling.ipynb`
In this notebook, we undertake the modeling phase, which involves:
- Implementing various regression models like KNN, Decision Tree, Ridge, Lasso, Polynomial Regression, and Support Vector Regression.
- Evaluating these models to select the best performer based on RMSE.
- Making predictions for 2023 traffic data and visualizing these predictions.

## Data Sources
The data used is from: [Statens vegvesen](https://trafikkdata.atlas.vegvesen.no/) and [Geofysisk institutt](https://veret.gfi.uib.no/).

## Usage
To work with the project:
1. Clone the repository.
2. Explore and run the Jupyter notebooks in order, starting with `data-preparation.ipynb`.
3. Review the generated files for further insights and predictions.

## Requirements
- Python with libraries like Pandas, NumPy, Plotly, Scikit-Learn, and Seaborn.
- Jupyter environment for running the notebooks.