# House Price Prediction using Linear Regression

## Project Overview
This project predicts house prices using Linear Regression. Exploratory Data Analysis (EDA), correlation analysis, model training, and evaluation were performed using Python.

## Dataset
- Dataset file: `housing_prices.csv`
- Rows: 50
- Columns: 21
- Target variable: `price`
- Missing values: 0

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Steps
1. Loaded and explored the dataset.
2. Checked missing values and descriptive statistics.
3. Visualized the distribution of house prices.
4. Created a correlation heatmap.
5. Selected bedrooms, bathrooms, sqft_living, sqft_lot, and grade as features.
6. Split the data into 80% training and 20% testing sets.
7. Trained a Linear Regression model.
8. Evaluated the model using MSE, RMSE, and R² score.
9. Created Actual vs Predicted and Residual plots.
10. Analyzed feature coefficients.

## Model Results
- Training rows: 40
- Testing rows: 10
- MSE: 4,976,395,285.00
- RMSE: 70,543.57
- R² Score: 0.6424

## Conclusion
The Linear Regression model explained approximately 64.24% of the variation in house prices in the test set. These results are preliminary because the dataset contains only 50 rows. A larger dataset would be needed for more reliable predictions.

## How to Run
1. Install the required Python libraries.
2. Place `housing_prices.csv` in the project folder.
3. Open `house_price_prediction.ipynb` in VS Code or Jupyter Notebook.
4. Run the notebook cells in order.

## Internship
Oasis Infobyte Data Analytics Internship — Level 2, Task 1

