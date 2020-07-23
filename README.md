# Sentiment_analysis_on_IMDB_movie_dataset

I'm using LSTM for sentiment analysis of IMDB movie review dataset. RNNs show excellent results(LSTMs to be precise) in NLP as it contains sequential data. I used pre-trained [Glove](http://nlp.stanford.edu/data/glove.6B.zip) word embeddings to obtain words vectors in our dataset. 



## Data
I used [IMDB movie review data](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews) which is a collection of 50000 movie reviews classified either as  positive or negative.


## Requirements

Python 3.7

Keras 2.3

Numpy 1.18

Pandas 1.0

Matplotlib 3.1


## Result 
I successfully obtained 90.82% accuracy on test set.
