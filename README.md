# Multi-Task-Learning
Build an NLP model that can detect tweets about disasters by performing two tasks that will be combined in a multi-task model. Given the text of a tweet, we will build NLP models to perform:
1. : Disaster detection: classify the tweet into one of two categories: “disaster” or “no
disaster”
2. : Sentiment classification: classify the sentiment of the tweet (next slide) to gauge the
severity of the tweet.

D1. : The dataset for Task 1 (Disaster classification).
Download the dataset from Kaggle.
Binary classification task with two labels (1) real disaster and (0) not a real disaster.
D2 : The labels for Task 2 (Sentiment classification) is not readily available in D1.
Therefore, we will obtain the labelled data for Sentiment classification task from
another Kaggle source. There are 3 sentiment labels in this D2 dataset: (0) Neutral (1) Negative, (2) Positive
In our application, this could used to gauge the severity of the tweet.


Four different Multi-Task Learning(MTL) models were assessed:
1) Hard parameter sharing model
2) Soft Parameter sharing model
3) Task Specific Attention Based MTL using hard parameter sharing layers
4) MTL using Random Forest model

The Assessment of these four models and discussion can be found under the notebook in this Repo.

