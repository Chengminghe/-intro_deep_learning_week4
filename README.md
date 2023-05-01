# Natural Language Processing with Disaster Tweets

This project uses Natural Language Processing (NLP) techniques to classify tweets as either related to a real disaster or not. The dataset used in this project is from Kaggle's "Real or Not? NLP with Disaster Tweets" competition, which can be found [here](https://www.kaggle.com/competitions/nlp-getting-started/data).

## EDA

The EDA (Exploratory Data Analysis) was done to understand the distribution of the tweets and the target classes. The distribution showed that there was a class imbalance between the disaster and non-disaster tweets. The tweets were further cleaned by removing URLs, punctuations, and special characters.

## Bidirectional LSTM

To classify the tweets as either disaster or non-disaster, a bidirectional LSTM model was used. Bidirectional LSTMs are a type of recurrent neural network that are commonly used for natural language processing tasks. The model was trained on the preprocessed tweets and used GloVe word embeddings for vectorization. The training data was split into a training and validation set, and the model was optimized using the binary cross-entropy loss function.

## Accuracy

The accuracy of the model was evaluated using the F1 score, which is the harmonic mean of precision and recall. The model achieved an F1 score of 0.93 on non-disaster tweets and 0.69 on disaster tweets, which is a good result considering the class imbalance in the dataset.

## Conclusion

In conclusion, this project demonstrates the effectiveness of using bidirectional LSTM models for NLP tasks such as tweet classification. The EDA helped to understand the distribution of the data and preprocess it for the model. The accuracy of the model achieved good results on non-disaster tweets and decent results on disaster tweets, considering the class imbalance in the dataset.
