# timeSeries-LSTM
Multivariate Time Series Forecasting with LSTMs in Keras


Source: https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/


```{bash}
conda create -n LSTM python=3.8
conda activate LSTM
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


## Single lag timestep
We will frame the supervised learning problem as predicting the pollution at the current hour (t) given the pollution measurement and weather conditions at the prior time step.

LSTM results in a persistence or naive model: 

**y(t) = y(t-1)**

![Screenshot_20220314_165428](https://user-images.githubusercontent.com/16523144/158210672-3f41d17c-1030-414f-9cd0-9a83785e5d0a.png)



## Multiple lag timestep




# Resources : 

- https://machinelearningmastery.com/convert-time-series-supervised-learning-problem-python/
- https://machinelearningmastery.com/time-series-forecasting-supervised-learning/
- https://machinelearningmastery.com/suitability-long-short-term-memory-networks-time-series-forecasting/
- https://machinelearningmastery.com/start-here/#lstm
