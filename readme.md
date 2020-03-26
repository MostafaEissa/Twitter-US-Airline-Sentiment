# Overview

A ULMFiT model for US airlines tweet sentiment analysis.  

# Dataset 

The dataset can be download from [here](https://www.kaggle.com/crowdflower/twitter-airline-sentiment#Tweets.csv) and consists of 13,640 tweets and contains whether the sentiment of the tweets in this set was positive, neutral, or negative for six US airlines.

Note: the dataset was  uploaded in this repository.

# Model

A pretrained language model on 103M wikipedia entries.

The model was fine tuned using [scikit-learn](https://scikit-learn.org/) and [fast.ai](https://docs.fast.ai/index.html).

# Metrics

The model achieved 78% accuracy on the validation set (random 20% subset of the training dataset) with an AUC score of 88%.