# Financial Planning

>In this Jupyter Lab, I am showing the analysis of the possibility of members to an emergency fund as well as the using the Monte Carlo simulations to create a financial planner for retirement.

The financial analysis includs the following:
    
* Using Alpaca API call to aquire up to date data

* Evaluating the emergency fund with created Pandas data frame

* Utilizing the MCForcastTools library to create a Monte Carlo simulation

* Visualizing the simulation results and probability distribution of the simulation

* Forcast the portfolio with a 95% confidence interval under different time frame
---

## Technologies
This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/docs/getting_started/overview.html) - To read, calculate, analysis, visualize data

* [pathlib](https://docs.python.org/3/library/pathlib.html) - For providing paths of files and directories

* [numpy](https://numpy.org/doc/stable/user/absolute_beginners.html) - To perform mathmatical calculations (squareroot).

* [alpaca_trade_api](https://github.com/alpacahq/alpaca-trade-api-python) - To import real time market data

* [os](https://docs.python.org/3/library/os.html) - Provides a portable way of using operating system dependent functionality

* [requests](https://www.w3schools.com/python/module_requests.asp) - To access data from another source

* [json](https://pypi.org/project/jsonlib/)- To translate JavaScript data to Python

* [dotenv](https://pypi.org/project/python-dotenv/)- To load environment variables
---

## Installation Guide

Before running the Jupyter notebook file, first, install the following dependencies in Terminal or Bash.

```python
  pip install pandas
  pip install pathlib
  pip install numpy
  pip install alpaca_trade_api
  pip install json
```

---

## Calculations and Visualizations

The following calculations and visualizations are used in the file:

* value of total stocks, bonds, and crypto currencies
* portfolio composition as of 2022-04-12
* emergency fund value
* total portfolio worth
* cumulative return of stocks and bonds
* 95% confidence interval invenstment return estimation

## Contributors

**UC Berkeley Extension**

**Yanjun Lin Andrie**

* yanjun.lin.andrie@gmail.com

* https://www.linkedin.com/in/yanjun-linked

---

## License

MIT
 