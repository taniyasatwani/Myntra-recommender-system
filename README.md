# Myntra recommender system / Image search
A deep learning model which recommends the top 5 similar items of user's interest.
 
![Web App GIF](https://i.imgur.com/GaDvTBS.gif)
![](predicted_stockprices.png)
![](predicted_stockprices_complete.png)

## Inspiration
A recommender system seeks to estimate and predict user content preference. The system draws from data usage history, aiming at making suggestions based on the user’s (current) interests.  

Most of the fashion purchases are when done when you see someone using the product and then after you look for the similar product or sometimes maybe the exact one. This thing cannot be achieved by the simple text search and to overcome it, we can use image search. So now whenever you find some interesting fashion, just click the photo of it, and search it using image search option. This will show the top 5 related fashion products which are related to the products in fashion.

## Dataset
![](Dataset link)[https://www.kaggle.com/paramaggarwal/fashion-product-images-small]

## Overview
Data is extracted using `tiingo api` of AAPL and is saved in `AAPL1.csv`. I used the `Close` column to train my model.The Close column refers to the price of an individual stock when the stock exchange closed the market for the day. Data is splited using the date column and is trained using `LSTM`. The model taked 100 days of input and predicts the stock of next day. In this project the model predicts stock prices of 30 days.

