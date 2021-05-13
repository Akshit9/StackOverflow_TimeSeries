# StackOverflow TimeSeries

- It is a Timeseries data to check whether timeseries data is stationary or not
- And it has been tested with the help of ADF Test (Dickey-Fuller Test)
- By ADF test we could figure out whether our timeseries is stationary or not.
- And, this project is gone through some cool visulizations to make more interesting over data.

# Code and Libraries

- Python version - 3.8

- IDE - Google Collaboratory

- Packages - Pandas, numpy, matplotlib, plotly, seaborn, ADF test

# EDA 

![weaf](https://user-images.githubusercontent.com/40689141/118131876-b1ccb900-b41c-11eb-90b7-a9c587680d31.png)
![download (1)](https://user-images.githubusercontent.com/40689141/118131956-c741e300-b41c-11eb-8a95-6b492417c415.png)

# ADF test

First created a helper function that has Moving average, to check the data flow with three different window sizes.

And then directly gone through ADF test using statsmodels

If data has null hypothesis then, it is not stationary

If data is stationary then reject the null hypothesis

# Hence our Timeseries data has unit root it is Stationary
