# Prophet: ML Automatic Forecasting Procedure

Prophet is a ML tool for producing high quality forecasts for time series data that has multiple seasonality with linear or non-linear growth. In fact, Prophet is a procedure for forecasting time series
data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. This is a Prophet model for time 
series prediction of energy consumption in various sensors of an IoT platform from Blueshift Big Data Company.

### Important links 

Homepage: https://facebook.github.io/prophet/

HTML documentation: https://facebook.github.io/prophet/docs/quick_start.html

Issue tracker: https://github.com/facebook/prophet/issues

Source code repository: https://github.com/facebook/prophet

Contributing: https://facebook.github.io/prophet/docs/contributing.html

Prophet R package: https://cran.r-project.org/package=prophet

Prophet Python package: https://pypi.python.org/pypi/prophet/

Release blogpost: https://research.fb.com/prophet-forecasting-at-scale/

Prophet paper: Sean J. Taylor, Benjamin Letham (2018) Forecasting at scale. The American Statistician 72(1):37-45 (https://peerj.com/preprints/3190.pdf).

### Install in Python
Prophet is on PyPI, so you can use pip to install it. From v0.6 onwards, Python 2 is no longer supported. 

### Install pystan with pip before using pip to install prophet

```
pip install pystan==2.19.1.1

pip install prophet
The default dependency that Prophet has is pystan. PyStan has its own installation instructions. Install pystan with pip before using pip to install prophet.
```


### Version 0.1 (2017.02.23)
Initial release

### License
Prophet is licensed under the MIT license.

