# Position-Salary-
"A Python script demonstrating Random Forest Regression using scikit-learn, including data loading, preprocessing, model training, evaluation, and visualization.
# Random Forest Regression Example

This repository contains a Python script demonstrating the implementation of a Random Forest Regressor using scikit-learn. The example is based on a simple dataset to predict salary based on position level.

## Dataset

The dataset used in this example is named `Position_Salaries.csv`. It should contain at least two columns: 'Position' and 'Salary'.

## Dependencies

The following libraries are required to run this script:

- pandas
- matplotlib
- seaborn
- sklearn
- numpy

You can install them using pip:






## How to Run

1. Make sure you have the required dependencies installed.
2. Upload the `Position_Salaries.csv` file to the same directory as the script, or modify the script to load the file from a different path.
3. Run the Python script.

The script will perform the following steps:

- Load the dataset.
- Preprocess the data (handle categorical features).
- Train a Random Forest Regressor model.
- Evaluate the model using Out-of-Bag score, Mean Squared Error, and R-squared.
- Visualize the regression results.
- Display a plot of one of the decision trees within the forest.

## Code Explanation

- **Data Loading and Preparation:** The script loads the CSV file into a pandas DataFrame. Categorical features are encoded using `LabelEncoder`, and numerical features are scaled.
- **Model Training:** A `RandomForestRegressor` is initialized and trained on the prepared data.
- **Model Evaluation:** The performance of the model is evaluated using standard regression metrics.
- **Visualization:** Matplotlib is used to visualize the actual data points and the predicted regression line. A plot of one of the individual decision trees is also generated to provide insight into the forest's structure.

## Customization

You can modify the `n_estimators` parameter in the `RandomForestRegressor` to experiment with different numbers of trees in the forest.

Feel free to adapt this code for your own regression problems by replacing the dataset and adjusting the feature selection and preprocessing steps as needed.
