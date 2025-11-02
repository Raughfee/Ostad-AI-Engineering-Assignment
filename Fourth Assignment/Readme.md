Module 4 Assignment
📝 Linear Regression Assignment: California Housing Price Prediction
Part 1: Data Loading, Preprocessing, and Initial Linear Regression (35 Marks)


Task 1.1: Load and Prepare the Data (15)
1. Load the California Housing dataset from sklearn.datasets.fetch_california_housing.

2. Examine the features and the target variable (median house value).

3. Split the data into training and testing sets (e.g., 80% train, 20% test). Standardize the feature data using StandardScaler from sklearn.preprocessing on the training set, and then apply the same scaling to the test set.

Task 1.2: Train the Simple Linear Regression Model (10)
1. Instantiate and train a standard Linear Regression model (sklearn.linear_model.LinearRegression) using the standardized training data.

2. Make predictions on the test set.

Task 1.3: Evaluate the Simple Linear Regression Model (10)
1. Calculate and report the following evaluation metrics for the test set predictions:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE) (Calculate this from the MSE)

R-squared score

2. Briefly interpret the meaning of the R-Squared in the context of this problem.

Part 2: Regularized Linear Models (Lasso and Ridge) (30 Marks)


Task 2.1: Implement Ridge Regression (15)
1. Instantiate and train a Ridge Regression model (sklearn.linear_model.Ridge). Start with a regularization strength (alpha) of alpha = 1.0.

2. Make predictions on the test set.

3. Calculate and report the same four metrics (MAE, MSE, RMSE, R-Squared for the Ridge model's predictions.

34. Compare the R-Squared of the Ridge model to the R-Squared of the simple Linear Regression model.

Task 2.2: Implement Lasso Regression (15)
1.Instantiate and train a Lasso Regression model (sklearn.linear_model.Lasso). Start with a regularization strength of alpha = 0.01.

2. Make predictions on the test set.

3. Calculate and report the same four metrics (MAE, MSE, RMSE, R-Squared) for the Lasso model's predictions.

4. Analyze the Coefficients: Print the coefficients learned by the Lasso model. Briefly explain the primary difference between Ridge and Lasso in terms of how they affect the model's coefficients.

Part 3: Analysis and Observation (35 Marks)


Task 3: Final Comparison and Conclusion
1. Create a summary table comparing the R-Squared scores and RMSE values for the three models.


2. Based on the results, which model performs the best for predicting median house values in California? Justify your choice by referencing the evaluation metrics.

3.Briefly explain the role of regularization (both Ridge and Lasso) in the context of preventing overfitting.
