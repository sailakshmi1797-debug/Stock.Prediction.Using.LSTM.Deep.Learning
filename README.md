Stock Price Prediction using LSTM 

📌 Project Overview

This project uses Deep Learning to predict the future closing price of a stock (e.g., Apple, Google, or Tesla) based on historical price data. By leveraging an LSTM (Long Short-Term Memory) network, the model captures the temporal patterns and trends in financial time-series data. 

📈 Key Features

1.Real-time Data: Fetches the latest stock market data using the yfinance API.

2.Time-Series Processing: Uses a sliding window approach (e.g., using the last 60 days of data to predict the next day).

3.Data Normalization: Scales data between 0 and 1 using MinMaxScaler to improve neural network training speed and accuracy.

4.Performance Tracking: Visualizes the predicted vs. actual stock prices using Matplotlib. 

🛠️ Tech Stack

1.Language: Python
2.Deep Learning: TensorFlow / Keras
3.Data Source: yfinance (Yahoo Finance)
4.Processing: Pandas, NumPy, Scikit-Learn
5.Visualization: Matplotlib 

⚙️ Model Architecture

1.Input Layer: Sequence of historical stock prices (e.g., 60 timesteps).
2.LSTM Layers: Two or more LSTM layers to extract complex patterns.
3.Dropout Layers: Added to prevent overfitting during the training phase.
4.Dense Layer: A final output layer to predict the single value for the next day's price. 

💡 Key Results

Root Mean Squared Error (RMSE): 
Conclusion: The model effectively tracks stock trends, though it is intended for educational purposes and not financial advice. 
