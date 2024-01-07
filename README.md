# Predicting Stock Prices Using LSTM 💹

In today's financial landscape, predicting stock prices is a vital aspect of investment decision-making. Machine learning, particularly Long Short-Term Memory (LSTM) models, has gained significant traction for its ability to capture complex temporal patterns in sequential data, making it a powerful tool for stock price prediction.

## Objective 🚀
This project aims to delve into the world of LSTM-based stock price prediction by leveraging historical stock market data to build and train an LSTM model capable of forecasting future stock prices.

## Libraries Used 📚
- Pandas for data manipulation 🐼
- Matplotlib for visualization 📊
- TensorFlow for machine learning 🤖
- NumPy for numerical operations 🔢

## Overview 📝
### Loading and Sorting Data 📈
- Data is fetched from a provided URL and structured into a Pandas DataFrame.
- The data is sorted based on the 'Date' column to ensure chronological arrangement.

### Visualizing Stock Prices 📉
- A line plot is generated to visualize the mid-price of stocks over time, aiding in understanding the general price trend.

### Preprocessing Data 🔧
- Data undergoes smoothing and normalization processes.
- Exponential Moving Average (EMA) is applied for smoothing.

### Data Generator Class 🔄
- A class is defined to generate batches of data for an LSTM model, ensuring proper formatting for training.

### LSTM Model Setup 🧠
- Placeholders for input and output sequences are defined along with LSTM model parameters like the number of nodes and layers.

### TensorFlow Graph for LSTM 📊
- The TensorFlow graph for the LSTM model is set up, including defining LSTM cells, weights, biases, and initial states.

### Training the LSTM Model ⚙️
- The LSTM model is trained using prepared data by iterating through epochs and updating model weights.

### Predicting and Validating 🎯
- Model predictions are generated and validated against test data, with the learning rate dynamically adjusted based on test error.

### Plotting Predictions 📈
- The evolution of test predictions over time is visualized to observe how model predictions change with each epoch.

## Running the Code ▶️
To run this project, ensure the necessary libraries are installed. Run the provided code in a Python environment supporting TensorFlow.
