# TimeSeries Analysis on Dublin_Bikes Data to predict bikes availability in future

The dataset provided is of Dublin Bikes. This is a time series data set where in readings have been taken at every 5mins. The downloaded dataset (Quarter-1 of 2020) has the following columns ['STATION ID', 'TIME', 'LAST UPDATED', 'NAME', 'BIKE STANDS', 'AVAILABLE BIKE STANDS', 'AVAILABLE BIKES', 'STATUS', 'ADDRESS', 'LATITUDE', 'LONGITUDE'].

The requirement is to predict bike station occupancy 10 mins, 20 mins, 60 mins in the future.

Did data pre-processing and exploratory data analysis followed by implementation of Ridge Regression and Random Forest Regressor models. 
After hyper parameters tuning and feature selection, the Mean squared error for Ridge was found to be 2.1297, 6.6463 and 12.7422 for 10 mins, 30 mins and 60 mins respectively. Whereas, for random forest, it was found to be 0.6455, 0.9754 and 1.1246 10 mins, 30 mins and 60 mins respectively.
