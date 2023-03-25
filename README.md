# Air Quality in Lagos
this project utilizes  data from one of Africa's largest open data platforms openAfrica.The major purpose of this project is to build a time series model to predict air quality data from lagos by predicting it's PM 2.5 readings throughout the day.

 # Data
 The data used in this project is available from [openAfrica](https://africaopendata.org/). It is stored in a MongoDB database.
 
 # Methodology
The methodology used for predicting air quality in Lagos using time series analysis is as follows:

**Data Wrangling:** For this project a wrangle notebook was uploaded.This notebook contains the code in pymongo used to wrangle the data from the MongoDB database, as well as the Python code used to convert the data to a dataframe, Series and performed initial exploratory analysis.
 
**Time Series Analysis:** For this task two notebooks where uploaded the first is for using time seres to evaluate linear regression,while the other was characterized with autoregrssive model.Time series analysis techniques such as autocorrelation analysis was applied to the data.

**Model Training:** To ensure that the models generalized well to new, unseen data, I split the data into training and test sets using a variable named  cut off. The size of the train set was about 90% of the total data.

**Model Evaluation:** To evaluate the performance of the model the  metrics  MAE was utilized .

# Conclusion
Predicting air quality in Lagos using time series analysis is a challenging task due to the complexity of the data and the presence of multiple pollutants. However, with the right methodology and techniques, it is possible to develop a reliable model for predicting air quality. The methodology outlined in this repository provides a framework for predicting air quality in Lagos using time series analysis.

# Usage
To use the models, you can run the Jupyter notebooks provided. The notebooks have detailed explanations of the steps taken and the code used.