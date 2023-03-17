# Sales Forecasting Solutions

<p align="center">
  <img src="https://www.saleshacker.com/wp-content/uploads/2017/05/sales-forecasting-metrics-1024x768.jpg" />
</p>

For this project we are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and participants must project the sales for each department in each store. In this first version of the project the objective will be: 

* Predicting store-level sales behavior through time series modeling with some of the libraries available in Python

* Generate a sales visualization and analysis tool using a BI solution

**Note: I have divided the project into several notebooks for each of the models used for sales forecasting. I also recommend to check the notebooks in Kaggle because in Github the plotly graphs are not displayed. I leave the link below:**


* [Exploratory Data Analysis](https://www.kaggle.com/code/armandodelahoya/walmart-sales-forecasting-eda/notebook)
* [Prophet model](https://www.kaggle.com/code/armandodelahoya/walmart-sales-forecasting-prophet-model/notebook)
* [Neural prophet model](https://www.kaggle.com/code/armandodelahoya/walmart-sales-forecasting-neural-model/notebook)
* [PyCaret library](https://www.kaggle.com/code/armandodelahoya/walmart-sales-forecasting-pycaret-library/notebook)
* [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNWFjYWU0ZTktNjFiYS00Zjg3LTg0M2MtOTMzM2M0MjQ5OThmIiwidCI6IjAyNDlhNTcxLWI5YTItNGNhMi1iOTNiLTIwYzc3MDg4ZjA4YiJ9)
* [Github repository](https://github.com/ArmandoLazalde/Walmart-Sales-Forecasting)


## Results

* By evaluating with the MAPE metric we obtain acceptable performance. However, it is possible to improve both models by considering exogenous variables provided in the dataset such as temperature, CPI, and inflation rate. As well as regressors or a combination of more sophisticated models.

* Both, Prophet and Neural Prophet, present good results, however, the former has shorter run times when working with a large number of stores.

* The application of sales forecasting with these models is intuitive and user-friendly for data scientists.
