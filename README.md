# Stock Market Prediction using Numerical and Textual Analysis

This project is a part of The Sparks Foundation GRIP internship and highlights time series analysis of historical stock prices and sentiment analysis of news headlines.

## Datasets
- **Historical Stock Prices Dataset:** Extracted from [Yahoo Finance](https://finance.yahoo.com/)
- **News Headlines Data:** Available from [bit.ly/36fFPI6](https://bit.ly/36fFPI6)

## Methodologies

### 1. Time Series Analysis
I have used the Auto-ARIMA model to predict stock market prices using historical stock prices data.

### 2. Sentiment Analysis
For the sentiment analysis model, various machine learning algorithms have been employed, including:
- Random Forest Regressor
- LightGBM
- AdaBoost
- XGBoost

## Project Structure
The repository is structured as follows:
- `data/`: Contains the datasets used for the project.
- `notebooks/`: Jupyter notebooks used for data analysis and modeling.
- `models/`: Saved models.
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `README.md`: Project overview and instructions.

## Installation
To run this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/jiya07/Stock-Market-Prediction-using-Numerical-and-Textual-Analysis.git
    cd Stock-Market-Prediction-using-Numerical-and-Textual-Analysis
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To train the models and make predictions, run the following command:
```bash
python src/main.py
