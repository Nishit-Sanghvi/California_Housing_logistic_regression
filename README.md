# Housing Prices Prediction using Linear Regression

This project demonstrates the implementation of a **Linear Regression Model** to predict housing prices using a dataset. It involves data preprocessing, feature transformation, and training a regression model to estimate housing prices.

## Features of the Project

- **Data Preprocessing**:
  - Handled missing values in numerical columns.
  - Categorical feature (`ocean_proximity`) was encoded using One-Hot Encoding.
  - Features were standardized using `StandardScaler`.

- **Model Training**:
  - Used **Linear Regression** from `scikit-learn` to fit the preprocessed data.
  - The dataset was divided into features (e.g., `longitude`, `latitude`, `median_income`, etc.) and target (`median_house_value`).

- **Model Evaluation**:
  - Calculated the **Root Mean Squared Error (RMSE)** to measure prediction accuracy.
  - Identified underfitting due to a large prediction error (~69,130.35) compared to the mean house value (~206,855.82).

---

## Dataset

The dataset includes the following features:

- `longitude` and `latitude`: Geographic coordinates of the property.
- `housing_median_age`: Median age of houses in the area.
- `total_rooms` and `total_bedrooms`: Total number of rooms and bedrooms.
- `population` and `households`: Population and households in the area.
- `median_income`: Median income of residents.
- `ocean_proximity`: Categorical feature indicating proximity to the ocean.

---

## Prerequisites

To run the notebook, you need the following installed:

- Python (3.8 or higher)
- Jupyter Notebook
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib` (optional for visualizations)

Install the required libraries using:

```bash
pip install pandas numpy scikit-learn matplotlib
```

---

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Nishit-Sanghvi/California_Housing_logistic_regression.git
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Housing_linear_regression_RMSE.ipynb
   ```

3. Run the cells sequentially to preprocess the data, train the model, and evaluate its performance.

---

## Results

- **Training Error**:
  - RMSE: ~69,130.35
- **Observation**:
  - The model underfits the training data, indicating it may not have enough capacity or complexity to capture the underlying patterns.

---

## Future Improvements

- Use more complex models like Decision Trees or Random Forests.
- Perform hyperparameter tuning.
- Visualize relationships between features and target values.

---

## Contributing

Feel free to fork this repository and submit pull requests. Suggestions and improvements are welcome!

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Let me know if you'd like to include more sections, or customize it further!
