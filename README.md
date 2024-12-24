# Linear-Regression-project

This project aims to predict energy prices using a linear regression model implemented from scratch. The dataset used for this project contains various features related to energy generation and consumption.

## Dataset

The dataset used in this project is `energy_dataset.csv`, which contains the following columns:

- time
- generation biomass
- generation fossil brown coal/lignite
- generation fossil coal-derived gas
- generation fossil gas
- generation fossil hard coal
- generation fossil oil
- generation fossil oil shale
- generation fossil peat
- generation geothermal
- generation hydro pumped storage aggregated
- generation hydro pumped storage consumption
- generation hydro run-of-river and poundage
- generation hydro water reservoir
- generation marine
- generation nuclear
- generation other
- generation other renewable
- generation solar
- generation waste
- generation wind offshore
- generation wind onshore
- forecast solar day ahead
- forecast wind offshore eday ahead
- forecast wind onshore day ahead
- total load forecast
- total load actual
- price day ahead
- price actual

## Data Preprocessing

The following preprocessing steps were performed on the dataset:

1. Dropped columns with a high percentage of missing values.
2. Dropped rows with any missing values.
3. Scaled the features using `MinMaxScaler`.

## Model Training

A linear regression model was trained using the preprocessed dataset. The model was implemented from scratch and trained using the following steps:

1. Split the dataset into training and testing sets.
2. Computed the cost function and gradients.
3. Performed gradient descent to optimize the model parameters.

## Model Evaluation

The model was evaluated using the Mean Squared Error (MSE) and R-squared (R²) metrics. The results are as follows:

- **Mean Squared Error (MSE):** 94.049
- **R-squared (R²):** 0.516

## Results

The model's predictions were compared to the actual prices, and the results were visualized using scatter plots and histograms.

## Conclusion

The linear regression model achieved an R-squared value of 0.516, indicating that the model explains approximately 51.6% of the variance in the energy prices. This suggests that while the model has some predictive power, there is still room for improvement.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.