**Sunspot Forecasting**


This repository contains models and data used to forecast sunspot activity over daily, monthly, and yearly intervals. The project uses time series forecasting techniques to predict future sunspot numbers based on historical data.

**Files in this Repository**

1) **Daily.ipynb**


This Jupyter Notebook contains the model for forecasting sunspot activity on a daily basis using a linear growth model. It uses daily historical sunspot data and predicts future daily values.


2) **Monthly.ipynb**


This Jupyter Notebook contains the model for forecasting sunspot activity on a monthly basis using a logistic growth model. It incorporates natural limits or caps in sunspot activity and is more suited for medium-term forecasting.


3) **Yearly.ipynb**


This Jupyter Notebook contains the model for forecasting sunspot activity on a yearly basis using flat growth. This model is suitable for long-term predictions, focusing on the cyclic behavior of sunspot activity over the years.


4) **SN_d_tot_V2.0 (1).csv**


A CSV file containing daily sunspot data. This dataset is used for the daily forecasting model.


5) **SN_m_tot_V2.0.csv**


A CSV file containing monthly sunspot data. This dataset is used for the monthly forecasting model.


6) **SN_y_tot_V2.0.csv**


A CSV file containing yearly sunspot data. This dataset is used for the yearly forecasting model.

**Install Dependencies** The notebooks require Python 3.x and the following libraries:


pandas


numpy


matplotlib


seaborn


fbprophet (for the forecasting models)


jupyterlab


You can install the dependencies using pip:



            pip install pandas numpy matplotlib seaborn fbprophet jupyterlab


Run the Notebooks
         
          Open Daily.ipynb, Monthly.ipynb, or Yearly.ipynb based on the data frequency you are interested in.


          Follow the instructions within the notebooks to run the analysis and make predictions.


**Project Overview**



This project aims to forecast sunspot activity using time series analysis. Sunspot numbers are recorded over various time scales, and different growth models are applied depending on the data frequency:



Daily Data: Linear growth model to predict daily variations.


Monthly Data: Logistic growth model to account for the natural saturation of sunspot activity.


Yearly Data: Flat growth model for long-term periodic behavior.


The goal of this project is to explore how sunspot data can be used for forecasting and to demonstrate the use of different time series forecasting methods.


**Challenges & Future Work**



Handling missing or inconsistent data.


Fine-tuning growth models for better accuracy.


Exploring other forecasting models like ARIMA or LSTM for improved performance.


Investigating the influence of external factors on sunspot activity (e.g., solar flares, magnetic fields).









