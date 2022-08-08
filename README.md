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
![A drawing of the information flow in the model](https://github.com/tensorflow/text/blob/master/docs/tutorials/images/bidirectional.png?raw=1)

# Train BERTs Model:
To train BERTs model run sentiment_berts.py

<img width="199" alt="bert_model" src="https://user-images.githubusercontent.com/84884991/183482796-c629aecb-3da9-453c-8572-5c726c9d8559.PNG">

