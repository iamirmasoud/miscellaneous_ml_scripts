# Miscellaneous Machine Learning Scripts

## About this Repo
This repository contains miscellaneous machine learning scripts and notebooks for data analysis, modeling, and visualization. 

## Preparing the environment
**Note**: I have tested the codes on __Linux__. It can surely be run on Windows and Mac with some little changes.

1. Clone the repository, and navigate to the downloaded folder.
```
git clone https://github.com/iamirmasoud/miscellaneous_ml_scripts.git
cd miscellaneous_ml_scripts
```

2. Create (and activate) a new environment, named `mis_env` with Python 3.7. If prompted to proceed with the install `(Proceed [y]/n)` type y.

	```shell
	conda create -n mis_env python=3.10
	source activate mis_env
	```
	
	At this point your command line should look something like: `(mis_env) <User>:miscellaneous_ml_scripts <user>$`. The `(mis_env)` indicates that your environment has been activated, and you can proceed with further package installations.

3. Before you can experiment with the code, you'll have to make sure that you have all the libraries and dependencies required to support this project. You will mainly need Python3.7+ and PySpark. You can install  dependencies using:
```
pip install -r requirements.txt
```

4. Navigate back to the repo. (Also, your source environment should still be activated at this point.)
```shell
cd miscellaneous_ml_scripts
```

5. Open the directory of notebooks, using the below command. You'll see all files appear in your local environment; open the first notebook and follow the instructions.
```shell
jupyter notebook
```

6. Once you open any of the project notebooks, make sure you are in the correct `mis_env` environment by clicking `Kernel > Change Kernel > mis_env`.




## Contents

data: Directory containing sample data files used in the scripts

**Imbalanced Data.ipynb**: Notebook demonstrating different techniques for handling imbalanced data

### RNN Example: 
Directory containing an example of a Recurrent Neural Network (RNN) implementation

**aclImdb:** Dataset used in the RNN Example.ipynb notebook

**RNN Example.ipynb:** Notebook demonstrating how to build an RNN model for sentiment analysis

### Time Series:
Directory containing various notebooks related to time series analysis:

**1. ACF and PACF.ipynb:** Notebook demonstrating Autocorrelation and Partial Autocorrelation plots for time series analysis

**2. AR Model.ipynb:** Notebook demonstrating Autoregressive (AR) models for time series forecasting

**3. MA Model.ipynb:** Notebook demonstrating Moving Average (MA) models for time series forecasting

**4. Augmented Dickey-Fuller Test.ipynb:** Notebook demonstrating the Augmented Dickey-Fuller (ADF) test for time series stationarity

**5. ARMA Model.ipynb:** Notebook demonstrating Autoregressive Moving Average (ARMA) models for time series forecasting

**6. ARMA Stock Forecasting.ipynb:** Notebook demonstrating ARMA models for stock price forecasting

**7. SARIMA Model.ipynb:** Notebook demonstrating Seasonal Autoregressive Integrated Moving Average (SARIMA) models for time series forecasting

**8. GARCH Model.ipynb:** Notebook demonstrating Generalized Autoregressive Conditional Heteroskedasticity (GARCH) models for time series volatility forecasting

**9. GARCH Stock Modeling.ipynb:** Notebook demonstrating GARCH models for stock price volatility modeling

**10. Stock Forecasting.ipynb:** Notebook demonstrating different time series models for stock price forecasting

**11. Time Series Data Preprocessing.ipynb:** Notebook demonstrating different techniques for preprocessing time series data

**12. VAR Model.ipynb:** Notebook demonstrating Vector Autoregression (VAR) models for multivariate time series forecasting

**13. Granger Causality.ipynb:** Notebook demonstrating Granger Causality tests for analyzing causal relationships between time series

**14. Undo Stationary Transformations.ipynb:** Notebook demonstrating how to reverse stationary transformations on time series data

**15. Model Selection (AIC-BIC).ipynb:** Notebook demonstrating how to use Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC) for model selection

**16. Anomaly Detection.ipynb:** Notebook demonstrating different techniques for detecting anomalies in time series data

**17. STL Decomposition.ipynb:** Notebook demonstrating Seasonal-Trend decomposition using Loess (STL) for time series decomposition

**18. Stock Forecasting.ipynb:** Notebook demonstrating different time series models for stock price forecasting

**19. Investing Stock Selection.ipynb:** Notebook demonstrating how to use time series analysis to select stocks for investment

**20. Bayesian Time Series.ipynb:** Notebook demonstrating Bayesian time series analysis for forecasting and modeling

## Structure of repo
```
├── data
│   └── diabetes.csv
├── Imbalanced Data.ipynb
├── README.md
├── RNN Example
│   ├── aclImdb
│   └── RNN Example.ipynb
└── Time Series
    ├── 10. Stock Forecasting.ipynb
    ├── 11. Time Series Data Preprocessing.ipynb
    ├── 12. VAR Model.ipynb
    ├── 13. Granger Causality.ipynb
    ├── 14. Undo Stationary Transformations.ipynb
    ├── 15. Model Selection (AIC-BIC).ipynb
    ├── 16. Anomaly Detection.ipynb
    ├── 17. STL Decomposition.ipynb
    ├── 18. Stock Forecasting.ipynb
    ├── 19. Investing Stock Selection.ipynb
    ├── 1. ACF and PACF.ipynb
    ├── 20. Bayesian Time Series.ipynb
    ├── 2. AR Model.ipynb
    ├── 3. MA Model.ipynb
    ├── 4. Augmented Dickey-Fuller Test.ipynb
    ├── 5. ARMA Model.ipynb
    ├── 6. ARMA Stock Forecasting.ipynb
    ├── 7. SARIMA Model.ipynb
    ├── 8. GARCH Model.ipynb
    ├── 9. GARCH Stock Modeling.ipynb
    └── data
```