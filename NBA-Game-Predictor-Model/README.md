# NBA Game Outcome Prediction Project

This project involves web scraping NBA stats and creating a machine learning model to predict the outcomes of NBA games.

## Project Overview

This project includes:
- Web scraping NBA stats from online sources
- Data parsing and preprocessing
- Feature engineering
- Model training and evaluation
- Prediction of game outcomes

## Dependencies

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- BeautifulSoup4
- Requests
- Matplotlib

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/nba-game-prediction.git
    cd nba-game-prediction
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Web Scraping NBA Stats**:
    - Open and run the `get_data.ipynb` notebook to scrape the NBA stats from the desired sources.

2. **Parsing and Preprocessing Data**:
    - Open and run the `parse_data.ipynb` notebook to parse and preprocess the scraped data.

3. **Training the Model**:
    - Open and run the `NBA_model.ipynb` notebook to train the machine learning model on the processed data.

## Methodology

1. **Web Scraping**: NBA stats are scraped using BeautifulSoup and Requests libraries.
2. **Data Parsing and Preprocessing**: The scraped data is cleaned and transformed into a suitable format for model training.
3. **Feature Engineering**: New features are created based on the available data to improve the model's predictive power.
4. **Model Training**: A machine learning model is trained to predict the outcome of NBA games.
5. **Prediction**: The model is used to predict the outcomes of future NBA games.

## Results

- The model's performance is evaluated based on accuracy, precision, recall, and other relevant metrics.
