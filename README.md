![header](pics/header.png)
# ELAN Stock Prediction
**This project** compares, evaluates, and predicts ELAN stock price using Monte Carlo Simulation, FB Prophet, SMA, k-Nearest Neighbors, Arima, LSTM, and EMA.
---
---

Content incudes:

* [Technologies](#technologies)

* [Approaches](#approaches)

* [Results](#results)

* [Contributors](#contributors)

---

## Technologies
Include but not limited to the following:
>This project leverages python 3.7

* [Alpaca API](https://alpaca.markets/docs/) - Collect live stock information

* [Monte Carlo Forecast Tools](https://www.palisade.com/monte-carlo-simulation/) - Visualize all possiblities

* [Prophet](https://pypi.org/project/fbprophet/) - Time series forcasting

* [Google Colab](https://colab.research.google.com/?utm_source=scs-index) - Jupyter Notebook function in browser

* [Pandas](https://pandas.pydata.org/) - Data analysis and manipulation

* [Scikit-learn](https://scikit-learn.org) - Supplies machine learning libraries for Python

* [Keras](https://keras.io) - Provides deep learning API for Python interface

* [Yahoo Finance](https://pypi.org/project/yahoo-finance/) - Aquire stock data from Yahoo! Finance

* [Tensorflow](https://www.tensorflow.org) - Supplies machine learning libraries for Python

---

## Approaches
* Comparing ELAN and LLY performance
* Predict ELAN cumulative returns
* Explore Machine Learning models:
    * Simple Moving Average (SMA)
    * k-Nearest Neighbor
    * Auto ARIMA
    * Long Short Term Memory (LSTM)
* Perform future price predictions with the best model (LSTM):
    * Predict future 300 days price using historical daily closing price
    * Predict future 56 weeks performance using historical weekly average closing price

---

## Results
LSTM machine learning model performs the best among all explored models, thus, future predictions will be performed on LSTM model.

![lstm](pics/lstm.png)


### **Historical daily closing price visualization**
![ori](pics/ori.png)
---
---
### **Future 300 days prediction using daily closing price**
![300](pics/300.png)
---
---
### **Future 56 weeks prediction using weekly average closing price**
![week](pics/week.png)
---
---

## Contributors

**Yanjun Lin Andrie** <span>&nbsp;&nbsp;</span> |
<span>&nbsp;&nbsp;</span> email: yanjun.lin.andrie@gmail.com <span>&nbsp;&nbsp;</span>|
<span>&nbsp;&nbsp;</span> [<img src="pics/linkedin.png" alt="in" width="20"/>](https://www.linkedin.com/in/yanjun-linked/)

**UC Berkeley Extension**

---

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
