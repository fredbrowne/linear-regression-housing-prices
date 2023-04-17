# Linear Regression for California Housing Prices

This project demonstrates the use of a simple linear regression model to predict California housing prices based on the median income of households.

## Dataset

The dataset used in this project is the California Housing Prices dataset, which is available on Kaggle:

[California Housing Prices Dataset](https://www.kaggle.com/camnugent/california-housing-prices)

## Requirements

To set up the environment and install the required libraries, follow these steps:

1. Install Python 3.7 or higher
2. Create a virtual environment:

```bash
python -m venv ml_project_1
source ml_project_1/bin/activate  # On Windows, use `ml_project_1\Scripts\activate`
```

3. Install the required libraries:
```bash
pip install numpy pandas scikit-learn matplotlib
```
## Usage

1. Download the California Housing Prices dataset from the link provided above and extract the 'housing.csv' file into the project folder.
2. Run the linear_regression.py script to train the linear regression model and evaluate its performance:

```bash
python linear_regression.py
```

This will output the Mean Squared Error (MSE) and R^2 score of the model, as well as display a plot of the actual and predicted housing prices.

## Jupyter Notebook

An interactive Jupyter Notebook version of this project is also available. To run the notebook, make sure you have Jupyter installed:

```bash
pip install jupyter
```

Then, launch the Jupyter Notebook server:

```bash
jupyter notebook
```

Open the `linear_regression_california_housing.ipynb` notebook in the browser, and you can interactively run the code, modify it, and see the results.
