#AI + Forex (USDJPY) Prediction Project

📈 This project explores forecasting USD/JPY exchange rate movements using a combination of traditional statistical analysis and machine learning (LSTM deep learning models). The goal is to test whether AI can improve prediction accuracy compared to simple baselines.


📊 Project Overview

Dataset: Historical USD/JPY prices and Nikkei 225 index (2010–2025), downloaded via Yahoo Finance.





Models Used:

Logistic Regression (baseline classification of up/down moves)

Random Forest Classifier

LSTM Neural Network (TensorFlow/Keras)

Features: Daily returns, lagged returns, and Nikkei correlations.

Target: Predict whether USD/JPY will go up (1) or down (0) the next day.






🚀 Methods

Data Collection

Fetched USD/JPY and Nikkei 225 data using yfinance.

Preprocessed data into returns and lagged features.

Modeling

Logistic Regression and Random Forest for classification.

LSTM for sequence learning on time-series data.

Evaluation

Accuracy, confusion matrix, and trading-signal backtesting.






📈 Results

Logistic Regression: ~XX% accuracy

Random Forest: ~XX% accuracy

LSTM: ~XX% accuracy (best performer)

(Replace XX% with your actual results – or I can help you calculate from your notebook!)







🛠️ Installation & Usage

1. Clone this repository:
git clone https://github.com/yourusername/ai-forex-usdjpy.git
cd ai-forex-usdjpy

2. Install dependencies:
pip install -r requirements.txt

3. Run the Jupyter Notebook:
jupyter notebook "AI + Forex (USDJPY) project (2).ipynb"








🔮 Future Improvements

Add more macroeconomic features (interest rates, US yields, oil prices).

Explore advanced deep learning models (GRU, Transformer).

Compare with technical indicators (RSI, MACD, Bollinger Bands).







📌 Author

👤 Orest

MSc Law & Finance, University of Leeds

Interested in finance, AI, and algorithmic trading




