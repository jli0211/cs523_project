# Sentiment Analysis (Tensorflow)

# Overview
Sentiment analysis that compares both models: RNN model vs. the BERTs Model that classifies text into 2 categories: positive or negative sentiments. The RNN model is structured as follows:
- First layer: encoder
- Second layer: Embedding
- Third Layer: Bidirectional RNN-LSTM
- Last layer: Dense layer

# Prerequisites:
- Tensorflow 2.x
- numpy
- matplotlib.pyplot
- Python 3.7.13

# Train RNN model: 
To train a model run sentiment_rnn.py

# Train BERTs Model:
To train BERTs model run sentiment_berts.py
![A drawing of the information flow in the model](https://github.com/tensorflow/text/blob/master/docs/tutorials/images/bidirectional.png?raw=1)
