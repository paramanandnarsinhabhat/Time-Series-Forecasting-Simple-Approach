
# Simple Average Time Series Forecasting

This repository contains a time series forecasting project implemented using the Simple Average method. The project aims to demonstrate the efficacy of this method in forecasting future values based on historical data.

## Overview

The Simple Average approach in time series forecasting assumes that the future value of a variable is the mean of all the past values. This method is straightforward and can serve as a baseline for more complex forecasting models.

## Dataset

The project utilizes two datasets: `train_data.csv` and `valid_data.csv`, which are used for training and validation purposes, respectively. Each dataset contains:
- `Date`: The date of observation.
- `count`: The target variable, which is forecasted using the Simple Average method.

## Requirements

The project relies on the following Python libraries:
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `matplotlib`: For visualizing data.
- `scikit-learn`: Specifically, for computing the root mean square error (RMSE).

## Implementation Details

The code includes several key steps:
1. Loading the data and performing basic preprocessing, such as converting date strings into datetime objects.
2. Plotting the training and validation data to understand the trends.
3. Applying the Simple Average method for forecasting. Two variations are used:
    - Average of the entire training dataset.
    - Average of the last week's data in the training set.
4. Visualizing the forecasts alongside the actual data for comparison.
5. Computing the RMSE to evaluate the performance of the Simple Average forecasts.

## Results

The RMSE values are calculated for both the complete data average and the last week's data average, providing a measure of the forecast accuracy.

## Visualizations

The script generates plots that compare the actual counts with the forecasts, illustrating the performance of the Simple Average method.

## How to Run

To execute the script, navigate to the project directory and run the Python file containing the code. Ensure that the data files are located in the specified directory.

## Contributing

Contributions, issues, and feature requests are welcome. 

## License

This project is licensed under the [MIT License](your-license-link).

