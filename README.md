# Sentiment Analysis (Tensorflow)
Multi-layer RNN used for Sentiment analysis in Python using tensorflow. 

Models from tensorflow text classification RNN and BERTs model. 

# Overview
Sentiment analysis that compares both models: RNN model vs. the BERTs Model that classifies text into 2 categories: positive or negative sentiments. The RNN model is structured as follows:
- First layer - encoder: converts the text into a sequence of token indices
- Second layer - Embedding: it stores 1 vector per word and when it is called, it converts the sequence of words into sequence of vectors
- Third Layer- Bidirectional RNN-LSTM: Combination of 2 RNNs (LSTM), one RNN moves forward and one moves backward. This allows the model to look at future context as well. 
- Last layer- Dense layer: layer that is deeply connected meaning that the neurons in the dense layer is receiving input from all the neurons from the previous layer. 

# Prerequisites:
- Tensorflow 2.x
- numpy
- matplotlib.pyplot
- Python 3.7.13

# Datasets:
- [IMDB Reviews](https://www.tensorflow.org/datasets/catalog/imdb_reviews) from Tensorflow Datasets
- [Sentiment 140 (Twitter Tweets)](https://www.tensorflow.org/datasets/catalog/sentiment140) from Tensorflow Datasets

# Train RNN model: 
To train a model run sentiment_rnn.py.
![A drawing of the information flow in the model](https://github.com/tensorflow/text/blob/master/docs/tutorials/images/bidirectional.png?raw=1)

# Train BERTs Model:
To train BERTs model run sentiment_berts.py

<img width="199" alt="bert_model" src="https://user-images.githubusercontent.com/84884991/183482796-c629aecb-3da9-453c-8572-5c726c9d8559.PNG">

# Comparison of the Two Models:
