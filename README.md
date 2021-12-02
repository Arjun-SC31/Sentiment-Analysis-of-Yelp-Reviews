# Sentiment-Analysis-of-Yelp-Reviews

The Yelp Dataset source: https://www.yelp.com/dataset/download [JSON format]

The stopwords, punctuation marks, and reviews in other languages are removed. For the context of analyzing sentiment, only the text and  the rating is required.

Plots for frequently occuring words in 1Star and 5Star reviews are plotted, along with the word clouds for the same.

The text is tokenized using countvectorizer.

FInally, review classification with the star rating being the target variable is performed.
The following algorithms were used and compared:

1. Multinomial Naive Bayes Classifier
2. Random Forest Classifier
3. Support Vector Classifier


Performance Metrics: Accuracy score, F-1 score, Confusion Matrics, Precision, Recall
The best performance metrics were observed in the support vector classifier.
