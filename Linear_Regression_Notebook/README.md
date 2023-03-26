# Linear Regression Using Time series for the Prediction of Air quality in Lagos
In this project i employed the technique of linear regression and i applied it on time series data.Usually when working with linear regression problems ,we are  charaterized with two variables namely the target and the feature variable but our data posessed a single column and target which was the PM2.5 reading. In other to do perform linear regression i lagged the PM2.5 readings by 1 hour, then i  treated the lagged column as the feature and performed my linear regression.Then predicted the qulaity of air in lagos in the coming hours.

# Data Splitting
Training and testing datasets were created from the data.The training set was 80% of the data while the 20% left  was used for testing.

# Model Buiding
I performed linear regression on the data using the scikit-learn library in Python.A linear regression model is a statistical model that is used to establish a relationship between a dependent variable (often denoted as Y) and one or more independent variables (often denoted as X). The relationship between these variables is assumed to be linear,which means that the change in Y is proportional to the change in X.  
 
# Performance Metric
The MAE (mean absolute error) was the performance metric used to evaluate our model. It measures the average absolute difference between the actual and predicted values of a target variable.

# Communication of results
After performing linear regression on the dataset  i derrived the  model below:

**P2 = 0.88 + (0.22 * P2.L1)**     where :

P2 = PM2.5 reading

0.88 = Intercept

0.22 = regression coefficient

P2.L1= lagged PM2.5 reading by 1 hour 