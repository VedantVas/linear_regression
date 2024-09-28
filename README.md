# linear_regression

---

# Linear Regression on CalCOFI Dataset

## Overview

This repository contains a Python script that performs **linear regression** on the **CalCOFI** dataset to explore the relationship between **salinity** and **temperature** in ocean water, which is simple model to illustrate how to make a linear regression model as a start.
You can find the dataset on Kaggle by CalCOFI dataset name and can directly download it from there. 

## What the Script Does

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

To install them, run:

```bash
pip install numpy pandas seaborn matplotlib scikit-learn
```

## How to Use

1. **Clone the Repository**:

```bash
git clone https://github.com/yourusername/calcofi-linear-regression.git
cd calcofi-linear-regression
```

2. **Run the Script**:

Make sure you have the dataset in the correct location or update the file path in the script:

```bash
python calcofi_regression.py
```

3. **Outputs**:
   - The script will display the R-squared score (a measure of how well the model fits).
   - It will also show two plots:
     1. A scatter plot with a regression line.
     2. A plot comparing actual vs predicted temperatures.

## What Each Part Does

1. **Load Data**: Reads the dataset and extracts two columns: salinity (`Salnty`) and temperature (`T_degC`).
2. **Preprocessing**: Fills missing values and splits the data for training and testing.
3. **Build Model**: Creates a linear regression model using the training data.
4. **Evaluate**: Calculates the R-squared score to see how well the model fits the data.
5. **Visualize**: Shows scatter plots and predictions.

## Example Outputs

- R-squared score on the full dataset:
  ```
  R-squared: 0.70 (example score)
  ```

- Example scatter plot and prediction plot will be shown as output.

## License

This project is licensed under the MIT License.

---

