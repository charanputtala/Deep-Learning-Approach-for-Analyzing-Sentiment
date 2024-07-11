# Deep-Learning-Approach-for-Analyzing-Sentiment

Predicting Personality Traits from Twitter Data: A Deep Learning Approach for Analyzing Sentiment during the Russo‐Ukraine War.
This project aims to predict the personalities of Twitter users based on their tweets related to the Russo-Ukrainian conflict. The researchers collected a dataset of 47,994 tweets containing various attributes like username, user ID, tweet text, hashtags, retweet count, etc.
After data pre-processing steps like removing URLs, symbols, converting to lowercase, the researchers used the Linguistic Inquiry and Word Count (LIWC) tool to analyze the linguistic and psychological characteristics of the tweets. LIWC provided scores on various dimensions like analytical thinking, clout, authenticity, emotional tone, etc which were used to calculate the "Big Five" personality traits - Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism (OCEAN scores).
With the OCEAN scores as features, the researchers tested several machine learning and deep learning algorithms to predict each user's personality type:

- Gaussian Naive Bayes achieved 77% accuracy
- Random Forest Classifier achieved 80% accuracy
- Support Vector Classifier (SVC) achieved 86% accuracy
- Multi-Layer Perceptron (MLP) achieved 88% accuracy
- Long Short-Term Memory (LSTM) achieved 91% accuracy
- Gated Recurrent Unit (GRU) achieved 92% accuracy
- Region-based Convolutional Neural Network (RCNN) achieved 95% accuracy

The RCNN model performed best with 95% accuracy in predicting personalities based on the OCEAN traits derived from tweet text data. However, the linguistic features from LIWC had some limitations in cases with unclear tweet information. The researchers suggest adding more contextual data and using feature selection could further improve prediction accuracy.
Overall, this novel application of personality prediction on social media data related to the Russia-Ukraine conflict demonstrates the potential of combining natural language processing, machine learning and psychological analysis techniques. The findings provide insights into how language use patterns can reveal underlying personality characteristics during major geopolitical events.
