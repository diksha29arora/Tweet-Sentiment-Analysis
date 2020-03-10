# Tweet Sentiment Analysis

The project is aimed at analyzing the sentiment of tweets using NLP and Deep Learning. 

It's trained on the Sentiment140 dataset with 1.6 Million tweets. I've used LSTM based neural network to train my model for Sentiment Analysis. The model occupies around 32GB of ram Hence, the Colab might need to be upgraded in case it crashes in the first time, as it provides us with only 12GB ram. 
The tweets were taken in a fixed length of 25 words. For the longer tweets, the last 25 words are taken into consideration and for the shorter ones are padded with zeros in the beginning. This model took almost 10 minutes to train on GPU. This way, I achieved a test accuracy of 84% in this by using a very basic LSTM based neural network.

(I implemented this project at the workshop on Deep Learning for Natural Language Processing.)
