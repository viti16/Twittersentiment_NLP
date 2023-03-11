This is a competition from Kaggle https://www.kaggle.com/competitions/nlp-getting-started .

Classify sentiment of tweet if it is reporting a real disaster(value=1) or not(value=0).

## Natural Language Processing with Disaster Tweets. Classify sentiment of tweet if it is reporting a real disaster(value=1) or not(value=0).

The data is taken from https://www.kaggle.com/competitions/nlp-getting-started

### Repo contains following files:
* `Notebook` contains the jupyter notebook that was used to perform machine learning task
* `test.csv,train.csv` Train and test data, test data is used to compute the accuracy in the competition

## General pipeline for this NLP task
* Cleaned the tweets to remove links, emoticons, non-alphanumerics, usernames etc.
* Created wordclouds of parts of data
* Removed stop words, created vocabulary, syntactic analysis, lemmatization, spelling check
* Cleaned and corrected the data using above steps
* Used sklearn word embedding to convert the documents and tokens into vectors
* Trained neural network on the dataset for prediction
* Crated a function to perform all the above steps on test data to predict the sentiment

## Results on kaggle account
https://www.kaggle.com/viti16
