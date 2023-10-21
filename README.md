
**In this project, we program a bot that automatically trades stocks for you. The bot
use sophisticated machine learning algorithms to predict future stock prices and then
decide to buy or sell the stock. We tested the performance of the bot empirically over a
certain time frame and for different stocks.**

#### Data
We collect your own stock price data for which we wanted to train the algorithms.

#### Tasks
• Choose a stock/index/currency/commodity/etc. and collect price data for a certain time
frame that we wanted to use to train and test the algorithms. 

• As a benchmark, we up with some rules to buy and sell the stock (i.e. buy the
stock if it was down the day before, ...). Also implemented an algorithm that buys the stock
at random. Tested the performance of the strategies empirically.

We used three ML algorithms:
  - Prophet
  - ARIMA
  - XGBoost

## Output:
For all the stocks we are getting profit which is close to optimum
 - We get 3.09 % return
 - For the same trading period and investment google provides more profit compared to apple and amazon
 - More complex rule using short selling could improve the net return, this need to be explored
 - ARIMA model performs well for returns forecasting
 - Its seems to be robust even for different period of time
 - Future steps would invove using Neural Network (NN) like Long Short Term Memory (LSTM) and having more sopisticated
   trading algorithum which not only consider historical data but also external input like correlation with other stocks price,
   technological changes, pandemic etc.
