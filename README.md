# Time-series-forecast
This folder contain all the material used in the MBA project done in ICMC USP, known as MBA IA and Big Data. The objective of the project is to forecast wind speed using statistical methods and machine learning models. In the statistical side, ARIMA and SARIMAX are considered meanwhile in the machine learning the Multilayer Perceptron and LSTMs are employed. The database can be requested by an email to fabioretorta@hotmail.com. Hands on in some coding! Best regards

In each .ipynb file there is an algorithm modeled to forecast the wind speed. In the ARIMA and SARIMAX it is recommended to forecast each day as granularity, since the computational burden to work with 10 minutes as time step can be unfeasible (e.g. no GPU).
In the statistical methods, statsmodel is the main package to simulate the data. In the machine learning algorithms, sklearn and keras libraries are fundamental to enable to model the artificial neural networks.
These methods can be found in the folder project:
ARIMA
SARIMAX
Multilayer Perceptron
LSTM Vanilla
LSTM Stacked
LST Bidirectional

The best results regarding RRMSE are provided by LSTM Vanilla. 
The difference in the performance metrics between statistical methods and ML are noticeable. 
The metrics differ just around 5% among the LSTM models. 
New simulations are welcome with different or better ML algorithms.
