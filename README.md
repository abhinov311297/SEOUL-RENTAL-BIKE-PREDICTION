# SEOUL-RENTAL-BIKE-PREDICTION
**LINEAR REGRESSION SUPERVISED MACHINE LEARNING**

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes. Data Description The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

## Variables

    Date : year-month-day
    Rented Bike count - Count of bikes rented at each hour
    Hour - Hour of he day
    Temperature-Temperature in Celsius
    Humidity- %
    Windspeed - m/s
    Visibility - 10m
    Dew point temperature** - Celsius
    Solar radiation - MJ/m2
    Rainfall - mm
    Snowfall - cm
    Seasons - Winter, Spring, Summer, Autumn
    
 ## STEPS
 
    1-PROBLEM STATEMNET-The main objective is to build a predictive model, which could help to train a model 
                        to predict the number of bike rentals of the year given the weather conditions.
    2-Importing the data
    3-Data Processing (Treatment of null values and outliers
    4-Exploratory Data Analysis
    5-Feature Selection
    6-Splitting the Data into train and test data
    7-Fitting the different model like (Linear Regression,Lasso,Ridge,Elastic,Random Forest Regression,Cross Validated Random ForesT,Polynomial Regression
    8-Evaluation of different model on different metrics like Mean Absolute Error,Mean Squared Error,Root Mean Squarede Error,R2_Score
    9-Comparison of different model
    10-Conclusion
  
 ## Conclusions-
 
During the time of our analysis, we initially did EDA on all the features of our datset. We first analysed our dependent variable, 'Rented Bike Count' and also transformed it. Next we analysed categorical variable and dropped the variable who had majority of one class, we also analysed numerical variable, found out the correlation, distribution and their relationship with the dependent variable. We also removed some numerical features who had mostly 0 values and hot encoded the categorical variables.

Next we implemented 6 machine learning algorithms Linear Regression,lasso,ridge,elasticnet,Random Forest and Polynomial Regression. We did hyperparameter tuning to improve our model performance. The results of our evaluation are:

