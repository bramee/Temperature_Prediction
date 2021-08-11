# Temperature_Prediction

- This data is for the purpose of bias correction of next-day maximum and minimum air temperatures forecast of the LDAPS model operated by the Korea Meteorological Administration over Seoul, South Korea. 
- This data consists of summer data from 2013 to 2017.Regressor
- The input data is largely composed of the LDAPS model's next-day forecast data, in-situ maximum and minimum temperatures of present-day, and geographic auxiliary variables. 
- There are two outputs (i.e. next-day maximum and minimum air temperatures) in this data. Hindcast validation was conducted for the period from 2015 to 2017.


Here We have 2 target variables and and as the data is numerical and continuous range ,it is REGRESSION Problem.

Here I have used the below algorithms to train and chosen the best model based on cross validation score,

  1) Support Vector Regressor
  2) Random Forest Regressor
  3) Linear Regression
  4) Ada Boost Regressor
  5) Gradient Boosting Regressor.
  
  
