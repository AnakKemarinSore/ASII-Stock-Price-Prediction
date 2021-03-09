# Astra International Stock Price Prediction using LSTM
Hej!

In this repository, we will try to predict stock price of Astra International (Astra). Astra is an Indonesian conglomerate (Indonesia-investment.com, 2014). This company was established in 1957 in Jakarta as a general trading company. In 1990, Astra has listed its shares on the Indonesia Stock Exchange under the ticker code ASII (Astra.co.id, 2021).

The objective of this project is to accurately predict Astra stock price.

Since stock price data is time-series data, it is essential to use a model that can predict time-series data accurately. Several popular models can be used to predict time-series data such as Long Short-Term Memory (LSTM) Network, Autoregressive Integrated Moving Average (ARIMA), and Facebook Prophet. For instance, Bao et al. implemented LSTM model for stock price forecasting (Bao et al, 2017), Pai and Lin used ARIMA and Support Vector Machines (SVM) model in stock price forecasting (Pai and Lin, 2004), Papacharalampous et al. implemented a Facebook Prophet for time-series forecasting (Papacharalampous et al, 2018). However, in this simple project, we will use LSTM to predict the stock price.

The LSTMs have recurrent connections; thus, the state of previous activations of the neuron from the previous time step is used as context for formulating an output (Brownlee, 2017). Besides, unlike other RNNs, LSTM has a unique formulation that allows it to avoid the problems that prevent the training and scaling of other RNNs. Therefore, it can achieve a better result. Those are the reasons why LSTM is gaining a lot of popularity for solving the time-series prediction case.

We will implement an interactive data visualization of stock price using Plotly! 

Note that we will use the LSTM model and the CRISP-DM reference model (adapted) as guidance to predict the ASII.JK stock price.


# Dependencies
There are some libraries that you should intall beforehand:
1. Pandas.
2. Numpy.
3. Keras.
4. Matplotlib.
5. Plotly.

# License
MIT License

# References
1. Astra International. (2021) About Astra. URL: https://www.astra.co.id/About-Astra
2. Bao, Wei, Yue, Jun & Rao, Yulei. (2017). A deep learning framework for financial time series using stacked autoencoders and long-short term memory. PloS one, 12(7), p.e0180944.
3. Brownlee, J. (2017) Long Short-Term Memory Networks With Python Develop Sequence Prediction Models with Deep Learning. Machine Learning Mastery, EBook.
4. Brownlee, J. (2018) How to Develop LSTM Models for Time Series Forecasting. URL: https://machinelearningmastery.com/how-to-develop-lstm-models-for-time-series-forecasting/
5. Chapman, P., Clinton, J., Kerber, R., Khabaza, T., Shearer, C., & Wirth, R. (2000). CRISP-DM 1.0: Step-by-step data mining guide. In The CRISP-DM consortium.
6. Indonesia-Investment.com. (2014) Astra International. URL: https://www.indonesia-investments.com/business/indonesian-companies/astra-international/item192
7. Loukas, S. (2020) Time-Series Forecasting: Prediction Stock Prices Using An LSTM Model. URL: https://towardsdatascience.com/lstm-time-series-forecasting-predicting-stock-prices-using-an-lstm-model-6223e9644a2f
8. Pai, Ping-Feng & Lin, Chih-Sheng. (2005). A hybrid ARIMA and support vector machines model in stock price forecasting. Omega (Oxford), 33(6), pp.497–505.
9. Papacharalampous, Georgia, Tyralis, Hristos & Koutsoyiannis, Demetris. (2018). Predictability of monthly temperature and precipitation using automatic time series forecasting methods. Acta geophysica, 66(4), pp.807–831.
10. Plotly. (2021). Plotly Python Open Source Graphing Library Financial Charts. URL: https://plotly.com/python/financial-charts/
