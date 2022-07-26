# Sentiment Analysis (Tensorflow)
Multi-layer RNN used for Sentiment analysis in Python using tensorflow.
Models from tensorflow text classification RNN and BERTs model. 
The BERTs Model used to run the Wikipedia Toxicity Subset Dataset is based on the model given in [Hugging Face](https://huggingface.co/docs/transformers/tasks/sequence_classification)

# Overview
Sentiment analysis that compares both models: RNN model vs. the BERTs Model that classifies text into 2 categories: positive or negative sentiments. The RNN model is structured as follows:
- First layer - encoder: converts the text into a sequence of token indices
- Second layer - Embedding: it stores 1 vector per word and when it is called, it converts the sequence of words into sequence of vectors
- Third Layer- Bidirectional RNN-LSTM: Combination of 2 RNNs (LSTM), one RNN moves forward and one moves backward. This allows the model to look at future context as well. 
- Last layer- Dense layer: layer that is deeply connected meaning that the neurons in the dense layer is receiving input from all the neurons from the previous layer. 

# Slideshow Link 

https://docs.google.com/presentation/d/187IqNFL61HfrSn01FwLqcec9LA-ipOsU7_t0bfRZtks/edit?usp=sharing


# Prerequisites:
- Tensorflow 2.x
- numpy
- matplotlib.pyplot
- Python 3.7.13
- Access to Google Colab

# Datasets:
- [IMDB Reviews](https://www.tensorflow.org/datasets/catalog/imdb_reviews) from Tensorflow Datasets
- [Wikipedia Toxicity Subtypes](https://www.tensorflow.org/datasets/catalog/wikiann)

# Train both RNN models: 
1. Copy the following google colab into your google Drive: [imdb_rnn](https://colab.research.google.com/drive/1z5yFfh1SqE7SpAu8AFBCENeHsjrXmZDs?authuser=1)
2. Load either the 'imdb_reviews' dataset or the 'wikipedia_toxicity_subtypes' dataset <img width="399" alt="image" src="https://user-images.githubusercontent.com/69744332/184056424-f62782b0-1ce9-4be7-820d-1f0f0628b670.png">

3. Under Runtime, click "Run all"
4. Repeat steps 1-3 for the other dataset


![A drawing of the information flow in the model](https://github.com/tensorflow/text/blob/master/docs/tutorials/images/bidirectional.png?raw=1)

# Train BERTs Model for IMDB:
1. Copy the following google colab into your google Drive: [berts_imdb](https://colab.research.google.com/github/tensorflow/text/blob/master/docs/tutorials/classify_text_with_bert.ipynb#scrollTo=4_NEJlxKKjyI)
2. Under Runtime, go to Change Runtime Type and change it into GPU

![image](https://user-images.githubusercontent.com/84884991/184053028-bb3d9dc9-95fd-40ab-b822-0ece462fcd7e.png)

3. Under Runtime, click "Run all"

# Train BERTs Model for Wikipedia:
1. Copy the following google colab into your google Drive: [berts_wiki](https://colab.research.google.com/drive/1PAd3amrW5PhMd_azZp3SJ_ZD4ncXn3fP?authuser=1)
2. Under Runtime, go to Change Runtime Type and change it into GPU

![image](https://user-images.githubusercontent.com/84884991/184053028-bb3d9dc9-95fd-40ab-b822-0ece462fcd7e.png)

3. Under Runtime, click "Run all"

![image](https://user-images.githubusercontent.com/84884991/184274949-c824000f-71d4-4712-85f2-62bc2aba9e07.png)


# Another way to Train the Models:
1. Download the files attached
2. Upload it to your Google Drive 
3. Go to [Google Colab](https://colab.research.google.com/?utm_source=scs-index) 
4. Open the file (depending on which model and dataset you want to train) 
5. Go to Runtime and click "Run all"
