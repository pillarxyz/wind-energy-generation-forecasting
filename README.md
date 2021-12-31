# Wind Energy Production Forecasting

In this project we use time series data about wind energy generation in germany to test and benchmark forecasting algorithms

## Data
The data folder contains the two original datasets :

* time\_series\_60min\_singleindex\_filtered.csv (wind power generation) 

* weather\_data\_filtered.csv (temperature data) 


these datasets that were download from [the OPSD Project](https://open-power-system-data.org/) are at an hourly rate from the start of 2017 till the end of 2019, we merged and resampled them into one dataset wind\_temp\_data.csv (daily)

## Notebook

the notebook wind-energy-production-forecasting.ipynb contains all the analysis and feature engineering we've done on the data
along with implementations of machine learning algorithms for forecasting like :

* ARIMAX
* Decision Trees
* Random Forests
* SVM
* ANN
* RNN
* LSTM

we also provided comparative metrics of all these algorithms at the end of the notebook
