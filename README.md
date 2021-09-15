# multi-strategy-trading-algo
Implementing and comparing the performance of three trading algorithms.

In this report I've used a synthetic dataset to evaluate the performance of three different trading strategies:
- Trend following based on EMA crossover;
- Mean reversion based on ARIMA model;
- Mean reversion based on ARIMA-GARCH model.

Mean reversion based on ARIMA strategy considerably outperforms the other strategies in the train set. However, the EMA crossover strategy performs
better on the test set. The cumulative performance of different trading strategies is summarised in the figure below:
