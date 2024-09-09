# Sneaker Resell Price Prediction Project

This project involves exploratory data analysis (EDA) and the creation of a machine learning model to predict sneaker resell prices. The main focus is on developing a model that can classify sneakers into high or low return on investment (ROI) categories.

## Project Overview

This project includes:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Feature selection
- Model training and evaluation
- Backtesting

## Dependencies

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sneaker-resell-prediction.git
    cd sneaker-resell-prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook Sneaker-Model.ipynb
    ```

2. Run the cells in the notebook to see the data processing, EDA, model training, and prediction steps.

## Methodology

1. **Data Cleaning and Preprocessing**: The dataset is cleaned to remove null values and irrelevant columns.
2. **Exploratory Data Analysis (EDA)**: Various visualizations are created to understand the distribution and relationships of the data.
3. **Feature Selection**: Features are selected based on their importance and correlation with the target variable.
4. **Model Training**: A RandomForestClassifier is used to train the model on the selected features.
5. **Prediction**: The model predicts whether a sneaker will have a high or low ROI.
6. **Backtesting**: The model's predictions are evaluated against a test set to assess its performance.

## Results

- The model achieved a precision score of 0.93 for the "High" ROI category, indicating high accuracy in predicting sneakers with high ROI.
