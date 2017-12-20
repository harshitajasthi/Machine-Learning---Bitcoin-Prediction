# Machine-Learning---Bitcoin-Prediction
## Motivation:
Bitcoin has been the talk of the town for a very long time and people are always looking for a way to predict the behaviour of bitcoin rise and fall. Our model is designed to do exactly that.
<br>
We are using real-time data and neural networks to achieve best results
<br>
## Tools Used:
1) Ipython Notebook jupyter<br>
2) Keras , Tensorflow

## Resources used:
The analysis decisions made strongly depend on research and Machine Learning Neural Network Lecture
<br>
This project has two parts 
<br>
1) Gathering Data
<br>
2) performing Analysis
<br>
3) comparing different models (coming soon)
<br>

<h4> Data Gathering </h4>
Data for the analysis is got from poloniex api and the ipython notebook for that is in bitcoin get data
<br>
Data we got was in json format so shapped it into a dataframe and stored in csv
(Based on flickr api lab)
<br>

<h4> Data Analysis </h4>
 Analysis is performed in the bitcoin prediction ipynb 
 <br>
 we are predicting next days data based on the previous day so our lookback is 1
 <br>
 the test dataset is going to be the last 14 days (2 weeks)
 <br>
 We have used LSTM neural network model , as our data has a lot of variation with time
 <br>
 Optimisier used is ADAM and since its regression analysis the loss function used is MSE

## Citations 
https://www.kaggle.com/kentata/rnn-for-predicting-closing-price-using-keras
<br>
https://www.kaggle.com/kentata/time-series-data-exploration
<br>
https://blog.patricktriest.com/analyzing-cryptocurrencies-python/

