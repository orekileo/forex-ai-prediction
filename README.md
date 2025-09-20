# AI + Forex (USD/JPY) Prediction Project
> Forecasting USD/JPY exchange rates with machine learning and statistical analysis.

![Python](https://img.shields.io/badge/python-3.10+-blue)
![License](https://img.shields.io/github/license/orekileo/forex-ai-prediction)

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Methods](#methods)
- [Results](#results)
- [Installation & Usage](#installation--usage)
- [Future Improvements](#future-improvements)
- [Author](#author)

---

## Overview

This project explores forecasting USD/JPY exchange rate movements using traditional statistical analysis and machine learning (LSTM models).  
The goal: predict whether USD/JPY will go up or down the next day.

---

## Dataset

- **Source:** Yahoo Finance
- **Period:** 2010–2025
- **Assets:** USD/JPY prices, Nikkei 225 index

---

## Models Used

- **Logistic Regression** (baseline classification)
- **Random Forest Classifier**
- **LSTM Neural Network** (TensorFlow/Keras)

**Features:**  
- Daily returns  
- Lagged returns  
- Nikkei correlations  

**Target:**  
- Next-day USD/JPY up (1) or down (0)

---

## Methods

**Data Collection**
- Fetch USD/JPY and Nikkei 225 using `yfinance`
- Preprocess: returns and lagged features

**Modeling**
- Logistic Regression & Random Forest for classification
- LSTM for sequence learning on time-series data

**Evaluation**
- Accuracy
- Confusion matrix
- Trading-signal backtesting

---

## Results

| Model               | Accuracy       |
|---------------------|---------------|
| Logistic Regression | 57.3%           |
| Random Forest       | 53.5%           |
| LSTM (best)         | 54.5%           |

---

## Installation & Usage

```bash
# 1. Clone this repository
git clone https://github.com/orekileo/forex-ai-prediction.git
cd forex-ai-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Jupyter Notebook
jupyter notebook "AI + Forex (USDJPY) project (2).ipynb"
```

---

## Future Improvements

- Add macroeconomic features (interest rates, US yields, oil prices)
- Explore advanced deep learning models (GRU, Transformer)
- Compare with technical indicators (RSI, MACD, Bollinger Bands)

---

## Author

**Orest**  
MSc Law & Finance, University of Leeds  
Interested in finance, AI, and algorithmic trading

[GitHub Profile](https://github.com/orekileo)

---
