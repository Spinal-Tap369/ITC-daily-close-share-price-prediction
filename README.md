# Do not use this to predict stocks irl. This is just a demo for a LSTM model

# Stock Price Prediction using LSTM

This project aims to predict stock prices using Long Short-Term Memory (LSTM) neural networks. It utilizes historical stock price data along with technical indicators to train an LSTM model for predicting future stock prices.

## Overview

- **Data Loading and Preprocessing**: Historical stock price data is loaded from a CSV file and preprocessed to compute technical indicators such as Moving Average (MA), Relative Strength Index (RSI), and Daily Returns.

- **Feature Scaling**: The input features are scaled using MinMaxScaler to ensure that all features are on a similar scale, which helps in improving the performance of the LSTM model.

- **Sequence Creation**: Sequences of input features and corresponding target prices are created to train the LSTM model. Each sequence contains a window of historical data along with the target price.

- **Model Training**: An LSTM-based neural network model is defined and trained using the training data. Training involves iteratively passing batches of input sequences through the model, computing loss, and optimizing model parameters using backpropagation.

- **Model Evaluation**: The trained model is evaluated on the test dataset to assess its performance using Mean Squared Error (MSE) loss. Additionally, the actual and predicted prices are plotted for visual inspection.

## Dependencies

- Python 3.x
- PyTorch
- pandas
- scikit-learn
- matplotlib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
