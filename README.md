# Coronavirus-Prediction
I tried to Predict No. of Confirmed cases, Active cases and Deaths in India and different states of India.
<br><br>
FOLDER <b>State - Wise Visualization</b>:

1.Create Data for States for Map.ipynb: This is the python file used to extract data from ‘IndividualDetails.csv’, and create another csv for individual States.
<br>2.Map Represent.ipynb: This is python file which plots data of Corona virus affected patients in each State to a Map of that state. For doing so, it requires shapefiles of each State.
<br>3.<a href = 'https://www.kaggle.com/sudalairajkumar/covid19-in-india#IndividualDetails.csv'>IndiviualDetails.csv </a>: Contains information of individual patients like date on which they were affected, city, State, etc. It is updated till 26.04.2020.
<br>4.Other files in the folder are shapefiles required for plotting the map of Rajasthan.

<br><br>
FOLDER <b>Corona virus State wise</b>:

<br>1.State-Wise Arima -New(11th May).ipynb: This is the python file used to predict corona virus spread in each State of India. Used ARIMA and SARIMAX models for training the data. And has used ‘covid_19_india.csv’ for the data.
<br>2.Recovery_days.ipynb: This is the python file used for analysis of the no. Of days it takes a person to recover from corona virus. For this data file used is - ‘IndividualDetails.csv’.
<br>3.<a href = "https://www.kaggle.com/sudalairajkumar/covid19-in-india">covid_19_india.csv</a>: This is the csv file which contains information like Date, Time, State, Confirmed, Cured, and Deaths. This data set is updated regularly and it has information till 11.05.2020.
<br>4.<a href = 'https://www.kaggle.com/sudalairajkumar/covid19-in-india#IndividualDetails.csv'>IndiviualDetails.csv</a>: Contains information of individual patients like date on which they were affected, city, State, etc. It is updated till 26.04.2020.


<br><br>
FOLDER <b>Corona virus India</b>:

<br>1.Arima Model prediction_new.ipynb: This is the python file used to predict total no. Of corona virus infected patients in India using ARIMA and SARIMAX model for training. It uses data from the file - ‘time_series_covid19_confirmed_global.csv’.
<br>2.Corona virus Prediction.ipynb: This is the python file used to Predict total no. Of Confirmed cases in India using Fbprophret. It also uses the same csv file.
<br>3.Active and Deaths Cases prediction.ipynb: This is the python file used to predict Total no. Of Active and deaths cases in India using ARIMA and SARIMAX model. For this it uses ‘time_series_covid19_confirmed_global.csv’, ‘time_series_covid19_recovered_global.csv’,
‘time_series_covid19_deaths_global.csv’
<br>4.<a href = "https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv">‘time_series_covid19_confirmed_global.csv’</a>: Contains data of all the countries In the world, and the data is updated every few hours.
<br>5.<a href = "https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv">‘time_series_covid19_recovered_global.csv’</a>:Contains data of all the countries In the world, and the data is updated every few hours
<br>6.<a href = "https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv">time_series_covid19_deaths_global.csv</a>:Contains data of all the countries In the world, and the data is updated every few hours
