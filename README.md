# Apple Stock Price Prediction

## Blog Link
https://github.com/diane3426/RNN-Stock-Prediction/blob/main/Final_Project_Python_File-1.ipynb

## Introduction
This project delves into the realm of financial market analysis by employing deep learning techniques to predict the closing prices of Apple Inc. (AAPL) stock. Deep learning, a subset of machine learning, utilizes neural networks with multiple layers to analyze vast datasets, uncover complex patterns, and make predictions. By applying these advanced tools to the volatile and data-rich domain of stock market prices, we aim to achieve high accuracy in forecasting the future values of Apple's stock, which is pivotal for investors and analysts alike in navigating the intricacies of the financial markets.

## Objective
The objective is to leverage advanced machine learning models to accurately forecast Apple's stock closing prices, providing valuable insights for firms to optimize trading strategies, manage risks, and enhance market efficiency.

## Dataset
The dataset comprises raw daily prices of Apple stock, spanning from 2010 to the end of 2016, with adjustments for stock splits. It includes features like the opening price, closing price, high, low, and volume of stocks traded.

## Model Used
- Linear Regression: Serves as a baseline model to understand the impact of individual variables on the stock price.
- Multi-layer Perceptron (MLP): A class of feedforward artificial neural networks designed to model complex relationships beyond linear interactions.
- Recurrent Neural Network (RNN): Ideal for time-series data due to its ability to capture sequence and time-dependent patterns.
- Long Short-Term Memory (LSTM): An advanced RNN that overcomes the limitations of traditional RNNs, particularly in learning long-term dependencies.

## Conclusion 
In conclusion, our project utilized deep learning models to predict Apple's stock prices, revealing nuanced insights into market dynamics. The validation error and mean squared error served as key metrics, showing that the MLP outperformed the linear regression model, likely due to its ability to capture non-linear relationships. Surprisingly, the RNN demonstrated lower error rates than the LSTM, suggesting that short-term trends might have a more significant impact on stock movements within our dataset. This project underscores the potential of neural networks in financial forecasting, providing a foundation for more informed investment strategies.
