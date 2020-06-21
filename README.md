# I build a Recurrent-Neural-Network and predict the Google Stock Price. (Time series forcasting)

Different ways to improve a RNN model:

(i) Getting more training data: I trained our model on the past 5 years of the Google Stock Price but it would be even better to train it on the past 10 years.


(ii) Increasing the number of timesteps: the model remembered the stock prices from the 60 previous financial days to predict the stock price of the next day. That’s because I chose a number of 60 timesteps (3 months). One could try to increase the number of timesteps, by choosing for example 120 timesteps (6 months).

(iii) Adding some other indicators: if you have the financial instinct that the stock price of some other companies might be correlated to the one of Google, you could add this other stock price as a new indicator in the training data.

(iv) Adding more LSTM layers: I built a RNN with four LSTM layers but one could try with even more.

(v) Adding more neurones in the LSTM layers: I chose to include 50 neurones in each of my 4 LSTM layers. One could try an architecture with even more neurones in each of the LSTM layers.
