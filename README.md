# Car Price Prediction Using Multiple Linear Regression

## Project Overview

This project uses Multiple Linear Regression, a supervised machine learning algorithm, to predict car prices based on different features.

The model predicts the price of a car using its manufacturing year, kilometers driven, and age.

## Features

- Load car dataset using Pandas.
- Select multiple independent variables.
- Train a Multiple Linear Regression model.
- Predict car prices for new inputs.
- Calculate regression intercept and coefficients.
- Evaluate model performance.
- Visualize actual vs predicted car prices.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Dataset Features

**Input Variables (Independent Variables):**
- Year
- Kms_Driven
- Age

**Output Variable (Dependent Variable):**
- Price

## Machine Learning Algorithm

Multiple Linear Regression

## Model Evaluation Metrics

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## Data Visualization

- Scatter Plot: Actual vs Predicted Prices
- Line Graph: Actual vs Predicted Prices
- Bar Graph: Actual vs Predicted Prices

## Installation

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## How to Run

1. Download or clone this repository.
2. Keep `carprice.csv` in the project folder.
3. Install the required libraries.
4. Run the Python file:

```bash
python main.py
```

## Example Prediction

```python
model.predict([[2025, 40000, 2]])
```

The model predicts the car price based on the given input features.

## Project Purpose

To understand and implement Multiple Linear Regression for real-world car price prediction using Python and Machine Learning.

## Author

Python Machine Learning Project

## License

MIT License
