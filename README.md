# timeSeries-LSTM
Multivariate Time Series Forecasting with LSTMs in Keras


Source: https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/


```{bash}
conda create -n LSTM python=3.8
```

```{python}
conda install -y numpy scipy matplotlib ipython pandas sympy nose
conda install -y -c conda-forge keras
conda install -y -c conda-forge tensorflow
conda install -y -c conda-forge scikit-learn 
conda install -y -c plotly plotly=5.6.0
```

```{bash}
python -m ipykernel install --user --name=LSTM
```


## Single lag timestep: 
We will frame the supervised learning problem as predicting the pollution at the current hour (t) given the pollution measurement and weather conditions at the prior time step.

## Multiple lag timestep: 




# Resources : 

- https://machinelearningmastery.com/convert-time-series-supervised-learning-problem-python/
- https://machinelearningmastery.com/time-series-forecasting-supervised-learning/
- https://machinelearningmastery.com/suitability-long-short-term-memory-networks-time-series-forecasting/
