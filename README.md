# sentiment-text-classifier
Comparing different ML models for sentiment classification based on movie review datasets. 

Here we first preprocess our datatset of 2000 movie reviews from the nltk corpus. These reviews have been divided into 2 classes, positive and negative. 

We extract the top 2000 most frequently used words in this corpus as our features and prepare a dataframe, where each moview review is represneted as a one hot encoded verion based on the extracted features. 

We then train our dataset using Naive Bayes classifier and Logisitic Regression to compare their accuracies. 
