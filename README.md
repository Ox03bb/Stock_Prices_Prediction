![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Tensorflow](https://img.shields.io/badge/-Tensorflow-ff6f00?style=flat&logo=tensorflow&logoColor=white) 

# Stock Prices Prediction

## Overview

This project aims to predict stock prices, specifically the Adjusted Close value, using machine learning techniques. The model utilizes various technical indicators as features to enhance prediction accuracy.

## Features

The following technical indicators are used as features to predict the Adjusted Close prices:

- **EMAF**: Exponential Moving Average Fast
- **EMAM**: Exponential Moving Average Medium
- **EMAS**: Exponential Moving Average Slow
- **MACD**: Moving Average Convergence Divergence
- **MACD Signal**: Signal line for MACD
- **BB_upper**: Bollinger Bands Upper
- **BB_middle**: Bollinger Bands Middle
- **BB_lower**: Bollinger Bands Lower

## Key Components

- **LSTM Layers**: Capture the temporal dependencies in stock price movements.
- **Bidirectional LSTM**: Enhances learning by looking at the sequence in both forward and backward directions.
- **Dense Layers**: Apply fully connected layers for the final predictions.
- **Dropout**: Helps prevent overfitting by randomly dropping units during training.

## Data

The model is trained using historical stock price data, with the previous price records serving as the basis for predicting the next day's Adjusted Close price. The features listed above are computed based on this data.

## Results

The model achieves a very good accuracy in predicting the Adjusted Close stock prices, thanks to the combination of advanced neural network architectures and carefully selected technical indicators.

## How to Run

#### Clone the repository:

```bash
git clone https://github.com/Ox03bb/Stock_Prices_Prediction.git
cd Stock-Prices-Prediction
```

#### Install the required dependencies:

```bash
pip install -r requirements.txt
```

