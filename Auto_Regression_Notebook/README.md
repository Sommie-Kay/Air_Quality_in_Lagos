# Predicting Air quality in Lagos Using An AutoRegressive Model.
An autoregressive model is a type of time series model that uses past values of the variable being modeled to predict future values. It is denoted as AR(p), where p represents the number of past time points used to predict the future value.For this project i derived an autoregressive model to predict air quality in lagos.

# Data Splitting
Training, testing, and walk-foward validation datasets were created from the data.The first 95% of the data is in my training set. The remaining 5% was used  in the test set.

# Model Building
I created an autoregressive model (AR) that uses past values of the variable to predict future values.

To determine the best value for p, a for loop was implemented to calculate the mean absolute error (MAE) for different values of p. The value of p that gave the lowest MAE was selected as the optimal value for our model, which was found to be 30.

To evaluate the performance of the model, walk-forward validation was performed on the entire test set (y_test), and the predictions were stored in the Series y_pred_wfv.

Overall, this model provides an accurate prediction of future values based on past data and can be used in various applications to make informed decisions.

# Performance Metric
The performance metric utilized was the MAE(mean absolute error).It is the average absolute difference between the predicted values and the true values.

# Communication of Results 
After performing a walk-foward validation of the test data set and result stored in a series i then ploted the result to test data shown in the visualization of this project and the test MAE beat the baseline which are clear indications that our model performed well and can be generalized.