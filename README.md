# MLP-TimeSeries-Forecaster

This project implements a Multilayer Perceptron (MLP) neural network for time series forecasting tasks. It demonstrates the process of training an MLP model on historical data and using it to predict future values of a time series.

## Dataset

The project uses the monthly international air passengers dataset (`AirPassengers.csv`), which contains the number of air passengers (in thousands) from 1949 to 1960.

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Usage

1. Clone the repository or download the source code.
2. Make sure you have the required dependencies installed.
3. Run the `mlp_lpid.py` script.

The script will perform the following steps:

1. Load and preprocess the air passengers dataset.
2. Visualize the time series data.
3. Decompose the time series into trend, seasonal, and residual components.
4. Reshape the data into a feature matrix using lagged values as input features.
5. Split the data into training and testing sets.
6. Standardize the feature and target variables.
7. Train an MLP model using a validation set for hyperparameter tuning (number of hidden nodes).
8. Evaluate the model's performance on the test set.
9. Generate forecasts for the test set using the trained MLP model.
10. Plot the original data, test data, and forecasted values.

## Customization

You can modify the code to experiment with different hyperparameters, such as the number of hidden layers, activation functions, or optimization algorithms. Additionally, you can adapt the code to work with other time series datasets by adjusting the data loading and preprocessing steps.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
