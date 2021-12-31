The data folder contains the two original datasets :

* time_series_60min_singleindex_filtered.csv (wind power generation) 

* weather_data_filtered.csv (temperature data) 

these datasets is at an hourly rate from the start of 2017 till the end of 2019, 
we merged and resampled them into one dataset wind_temp_data.csv (daily)

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
