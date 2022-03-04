# Sentiment-Analysis-of-Tweets
You are given a data of US Airline tweets and their sentiment. The task is to do sentiment analysis about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").


Objective
You are given a data of US Airline tweets and their sentiment. The task is to do sentiment analysis about the problems of each major U.S. airline. Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").


Things to do :
Read the tweets.csv data, clean and tokenize the tweets using nltk library.
Count vectorize the tweets so that you end up with a sparse matrix (which will be your  X ).
You are supposed to build a SVM classifier (a binary classification in fact). Since the data contains three levels of sentiment(positive, negative and neutral), you should remove the sentences which are neutral. Once you do that you will have two classes only (positive and negative). You can set the label of positive tweets to 1 and negative tweets to 0.
Once you have built the SVM classifier, evaluate this model across various metrics. Also plot the ROC curve and Precision-Recall curve. Report the areas under these two curves along with other metrics.
Perform GridSearch cross validation for various values of  C  and  gamma . These will be the hyperparameters which you would play around with.
Explain your observations and the underlying reasons for these.
Try checking if tfidfvectorizer helps you gain lift in model's performance.

