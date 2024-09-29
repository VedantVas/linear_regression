# linear_regression

---

# Linear Regression on CalCOFI Dataset

## Overview

This repository contains a Python script that performs **linear regression** on the **CalCOFI** dataset to explore the relationship between **salinity** and **temperature** in ocean water, which is simple model to illustrate how to make a linear regression model as a start.
You can find the dataset on Kaggle by CalCOFI dataset name and can directly download it from there. 

## What the we will do.

- Loads the CalCOFI dataset (salinity and temperature data).
- Fills any missing values.
- Splits the data into training and testing sets.
- Builds and trains a **linear regression model** to predict temperature from salinity.
- Visualizes the data and the model's predictions.
- Evaluates how well the model performs using the R-squared score.

## Requirements

You'll need the following Python libraries:

- `numpy`
- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`

## What Each Part Does

1. **Load Data**: Reads the dataset and extracts two columns: salinity (`Salnty`) and temperature (`T_degC`).
2. **Preprocessing**: Fills missing values and splits the data for training and testing.
3. **Build Model**: Creates a linear regression model using the training data.
4. **Evaluate**: Calculates the R-squared score to see how well the model fits the data.
5. **Visualize**: Shows scatter plots and predictions.

## License

This project is licensed under the MIT License.

---

