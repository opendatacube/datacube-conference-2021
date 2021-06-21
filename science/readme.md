Science topics
==============
`(DRAFT ONLY)`

Beginner's Sprint
-----------------
Self-guided work through weeks 3 & 4 of the training.digitalearthafrica.org course, followed by a use case looking at a SDG.

Change Detection
----------------
Teams will detect if and when land-clearing has happened within a given area, an generate mosaics of before and after the clearing event. 

Advanced: Time series forecasting of vegetation indices
------------------------------------------------------
This hack will explore scalable methods for short-term time-series predictions of remote sensing vegetation indices (e.g. NDVI, MSAVI). 
The output of this sprint should be one or two functioning jupyter notebooks that perform accurate short-term predictions of a nominated vegetation index, along with an account of the methods that failed. This work will hopefully inform future efforts at more advanced ecological forecasting.

### Possible approaches to explore
* [Prophet](https://facebook.github.io/prophet/docs/quick_start.html#python-api)
* [ml-forecast](https://pypi.org/project/mlforecast/)
* [autoregression](https://www.statsmodels.org/stable/examples/notebooks/generated/autoregressions.html)

### Notes and resources
* [Forecasting vegetation condition for drought early warning systems in pastoral communities in Kenya](https://www.sciencedirect.com/science/article/pii/S003442572030256X)
* Linear autoregression formula: `y = a + b1*X(t-1) + b2*X(t-2) + b3*X(t-3)`
* [Example forecasting in Python](https://pythondata.com/forecasting-time-series-autoregression/)
* [Autoregression Models for Time Series Forecasting With Python](https://machinelearningmastery.com/autoregression-models-time-series-forecasting-python/)
* [ScitKit-learn-Inspired Time Series models](https://github.com/EthanRosenthal/skits)
  * [Applied example](https://www.ethanrosenthal.com/2018/03/22/time-series-for-scikit-learn-people-part2/)
* https://www.machinelearningplus.com/time-series/time-series-analysis-python/


Advanced: Machine Learning Sprint
---------------------------------
The group will decide on a topic, and use training labels (possibly from Radiant Earth http://registry.mlhub.earth/) to train a model. 

