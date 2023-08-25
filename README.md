Task 2
ask: Predict the housing prices in a given area.
1. Load the housing prices data into memory and split it into input data (X) and output
data (y).
2. Split the data into training and test sets, with 80% of the data used for training and
20% of the data used for testing.
3. Create a linear regression model using the LinearRegression class from the scikit-learn
library.
4. Train the model on the training data using the fit method.
5. Make predictions on the test data using the predict method.
6. Calculate the mean squared error between the true output values (y_test) and the
predicted output values (y_pred) using the mean_squared_error function from the
scikit-learn library.
7. Print the mean squared error to the console.
8. Bonus: Try different values of the test_size argument in the train_test_split function
and observe how it affects the mean squared error. Can you find the optimal value of
test_size that gives the lowest mean squared error?


Although i have done the above task but i did not removed outliers from the dataframe, i think  if +_3.5 standard deviation is used to remove out liers we will have a better score and reduced MSE.
more over i droped only one column of "Country", in my oppinion multiple other columns should be droped for a better score of the predictive model and it will also substantially decrese the MSE.
