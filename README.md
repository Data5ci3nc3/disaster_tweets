# Disaster tweets projects
Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they are observing
in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies). But, it is not always
clear whether a person’s words are actually announcing a disaster.

## Goal to be achieved
The aim for this project is to attempt to build a machine learning model that predicts which Tweets are about real disasters and which ones are not.

## Methodology applied to reach the goal
- Conduct exploratory data analysis (EDA) to understand the data
- Data preprocessing
- Word embeddings and data preparation
- Creating a simple Recurrent Neural Network (RNN) model (baseline)
- Replacing the Simple RNN layers by Gated Recurrent Unit (GRU) layers
- Replacing the Simple RNN layers by Long short-term memory (LSTM) layers
- Summary and metrics of the three models tested

## Conclusion
The Gated Recurrent Unit (GRU) is the model which gives the best performance amongst the three models tested with the tweets dataset.
It is encouraging to have more or less good results for a first experience with Natural Language Processing (NLP). Nevertheless, I am not satisfied with my personal
comprehension of this complex subject. I will continue to practice again and again till I get more familiar with the different steps of the process.
