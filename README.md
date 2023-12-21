# House Pricing Prediction
House Pricing Prediction

# Conclusion
The Housing Price Prediction project aimed to design a regression model to predict the median house value based on various input attributes for California district blocks. The dataset consisted of geographical coordinates, housing statistics, and other relevant features.

## Overview
This project provides insights into predicting housing prices and serves as a foundation for further exploration and refinement of regression models.

The project involved several key steps:

1. **Data Loading / Preprocessing:**
   - Loaded the California housing dataset using `pandas.read_csv()` function.
   - Checked for missing values and dropped corresponding rows.
   - Created a correlation matrix to analyze the relationship between features and the target variable.
   - Split the data into features (X) and target (Y).

2. **Data Visualization:**
   - Visualized the distribution of key features using histograms.
   - Calculated and reported mean, median, and standard deviations for each feature.
   - Utilized one-hot encoding to convert categorical variables.

3. **Data Splitting:**
   - Split the data into training and test sets using the `train_test_split()` function.

4. **Data Scaling:**
   - Applied standard scaling to features and target values using `StandardScaler()`.
   - Ensured that both training and test sets were scaled appropriately.

5. **Modeling:**
   - Employed Linear Regression from `sklearn.linear_model`.
   - Fitted the model using scaled training data.
   - Utilized PCA to visualize the data in a reduced-dimensional space.

6. **Evaluation:**
   - Plotted a scatter plot to compare predicted and actual median house values.
   - Calculated MAPE, RMSE, and R2 to evaluate model performance.

7. **Discussion:**
   - Ranked continuous features based on the weights of the linear regression model.
   - Explored the relationship between feature influence and pair-wise correlation results.
   - Analyzed and interpreted the MAPE, RMSE, and R2 results.
   - Discussed the importance of centering and scaling data before performing PCA.

## Usage

To reproduce or extend this analysis:
   1. Load the provided data in housing.csv and Jupyter notebook.
   2. Execute each cell in sequence.
   3. Follow the steps for modeling, evaluation, and discussion.
   4. Adjust parameters or explore additional analyses as needed.
