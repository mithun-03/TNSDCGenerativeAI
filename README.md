# Machine Learning Models for Stock Prices Analysis 

This repository contains code for performing machine learning-based analysis on stock prices data. The provided code includes implementations of Ridge Regression using scikit-learn, as well as various Artificial Neural Network (ANN) architectures trained with gradient descent to minimize the cost function. Additionally, Long Short-Term Memory (LSTM) Memory Networks are trained and tested for stock prices prediction.

## Files Included:
ridge_regression_analysis.py: Python script for performing stock prices analysis using Ridge Regression from scikit-learn.
neural_network_models.py: Python script containing implementations of various ANN architectures trained with gradient descent.
lstm_memory_networks.py: Python script for training and testing LSTM Memory Networks for stock prices prediction.

## Usage:
To use the provided code:

Clone or download the repository to your local machine.
Ensure you have Python installed on your system along with necessary libraries specified in the requirements.txt file.
Execute the respective Python scripts for the analysis you want to perform:
For Ridge Regression analysis: Run python `ridge_regression_analysis.py`.
For training ANN models: Modify and run python `neural_network_models.py`.
For training and testing LSTM Memory Networks: Run python `lstm_memory_networks.py`.

## Libraries Used:
The code utilizes the following Python libraries:

NumPy
Pandas
Scikit-learn
TensorFlow (for LSTM Memory Networks)
Ensure you have these libraries installed before running the code.

## Data Requirements:
The code expects stock prices data in a specific format. Ensure your data follows these requirements:

The data should be in CSV format.
It should contain columns for 'Date', 'Open', 'High', 'Low', 'Close', and 'Volume'.
Date column should be in a format recognizable by Pandas (preferably YYYY-MM-DD).
Additional Notes:
The provided code is for educational and demonstration purposes.
It's recommended to understand the code and adapt it to your specific needs or datasets.
Ensure to set appropriate hyperparameters and tune the models as needed for optimal performance.
