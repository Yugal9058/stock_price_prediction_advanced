# stock_price_prediction_advanced
This repository contains an end-to-end stock price prediction system that uses Machine Learning and Deep Learning (LSTM) models to forecast future stock prices. The project demonstrates real-world ML workflow: data collection, feature engineering, model training, evaluation, and comparison.

🚀 Features

🔹 1. Automatic Data Download
Fetches historical stock data (default: AAPL – Apple Inc.) using yFinance.

🔹 2. Feature Engineering
Enhances dataset using technical indicators:
Moving Averages (MA10, MA50)
Exponential Moving Average (EMA20)
Relative Strength Index (RSI)
Daily returns

🔹 3. Machine Learning Models
Implements and compares:
Linear Regression
Random Forest Regressor

🔹 4. Deep Learning Model — LSTM
Uses Long Short-Term Memory networks to learn patterns from the last 60 days of prices and predict future values.

🔹 5. Visualizations
Generates comparison plots:
Actual vs Predicted (ML models)
Actual vs Predicted (LSTM)
Price trends
Saved in:
results/plots/

🔹 6. Modular Code Structure
All code is clean and production-ready inside /src/:
src/

│── data_loader.py

│── feature_engineering.py

│── models_ml.py

│── model_lstm.py

│── utils.py

└── train.py

🧠 Project Workflow

Download historical stock data
Clean & preprocess
Add technical indicators
Train ML models
Train LSTM model
Compare model performance
Visualize prediction curves

📂 Folder Structure

stock-price-prediction/

├── data/  # Downloaded raw stock data

├── notebooks/                 # Jupyter notebook for analysis

├── src/                       # All python modules

├── results/                   # Prediction plots & saved models

├── requirements.txt

└── README.md

🛠 Technologies Used

Python
Pandas, NumPy
Scikit-Learn
TensorFlow / Keras
yFinance
Matplotlib
▶️ How to Run the Project
1. Install dependencies
pip install -r requirements.txt
2. Run the training script
python src/train.py
3. Run the notebook
notebooks/stock_price_prediction_advanced.ipynb
📊 Results

Prediction graphs will be generated inside:
results/plots/
LSTM generally performs better than traditional ML models, especially for time-series forecasting.
🎯 Objective

To compare the effectiveness of:
Classical Machine Learning models
Deep Learning (LSTM)
for financial time-series prediction.
This project is designed to showcase knowledge of:
Data preprocessing
Feature engineering
ML/DL model development
Time-series forecasting
Modular project structuring
