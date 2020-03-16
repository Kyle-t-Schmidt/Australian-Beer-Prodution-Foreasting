# Australian-Beer-Prodution-Foreasting

## Introduction
The Australian Beer production data is a time-series dataset that gives the monthly beer production amount in megaliters between 1956 and 1996. The dataset can be found here: https://www.kaggle.com/shenba/time-series-datasets#monthly-beer-production-in-austr.csv

I will be forecating the next 12 months of beer production. In this program I demonstrate:

* R programming language
* Knowledge of statistics
* Knowledge of forecasting methods
* Time-series model and coeficiant estimation using autocorrelation and partial autocorrelation functions
* Data visualization

## Program purpose
I briefly explore the dataset, estimating the trend and seasonality before using both the Box-Jenking autoregressive integrated moving average and Holt-Winters Seasonal Smoothing methods to forecast future beer production

## Using the program
To run the program you will need to download the data, either from this repository or directly from the source and save it in your R working directory. After opening the .Rmd file you can either step through the program one chunk at a time or run all code. You will need to have R packages 'TSA' and 'Forecast' installed to run the program
