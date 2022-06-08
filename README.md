# Stock and Cryptocurrency Price Prediction Using Sentiment Analysis Project

## Int. to Natural Language Processing---DATA-690

In this course, I have performed multiple homeworks and 1 project.

This course aims to teach the use of natural language processing (NLP) as a set of methods for 
exploring and reasoning about text as data. The focus will be on the applied side of NLP. Students 
will use existing NLP methods and libraries in Python to textual problems. Topics include 
language modeling, text classification, sentiment analysis, summarization, recommending 
systems, chatbots, and machine translation. It is not a theory, nor a programming class. Students 
are expected to have a basic understanding of linear algebra, calculus, and probability concepts. 
The key concepts are explained in the required manuals and they will be mentioned in the lecture.

## Project Goal: 
The purpose of this study is to determine whether there is sufficient correlation between sentiment on social media, and real prices on the stock market in the U.S (New York Stock Exchange) to support stock price prediction. Social media data was gathered from Twitter and Reddit. Stocks used in this study are Apple, Tesla, Amazon, Microsoft, Google, Gamestop. Crypto currencies analyzed are Bitcoin, Ethereum, and Dogecoin. Sentiment scores were produced using the Vader Sentiment analysis. Model selection was performed using the Lazy Predict: LazyClassifier and LazyRegressor models. Results from the Lazy Predict model were analyzed and price prediction was performed using the RandomForestRegressor model from sklearn.ensemble. Results of the study reveal that the calculated mean absolute errors are low, the predicted prices are close to the actual prices, and there is a positive correlation between the sentiment and the price.

## Documentation
Refer to Report.docx for full report with images. 

## Summary of the files

* NLP_Project_model_Final:<br>
Models are created and tested on cleansed, useful data on this file. The results are shown with visualization. 

### Data Set 

* Twitter Data:<br>
Twitter data is gathered about related stocks and cryptocurrencies. 

* wallstreetbets:<br> 
Data gathered from subreddit named wallstreetbets in this file. (DM for this data set)

* Real Time Price Data:<br>
Real time price data for related stocks and cryptocurrencies are gathered here. 
