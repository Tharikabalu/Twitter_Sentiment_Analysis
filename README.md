# Twitter_Sentiment_Analysis
Classification of tweets into either positive or negative sentiments. This repository includes implementations of two machine learning algorithms for binary classification: Logistic Regression and Naive Bayes.
**Training naïve Bayes**
To train your naïve Bayes classifier, you have to perform the following steps:
1) Get or annotate a dataset with positive and negative tweets
2) Preprocess the tweets: process_tweet(tweet) ➞ [w1, w2, w3, ...]:
Lowercase
Remove punctuation, urls, names
Remove stop words
Stemming
Tokenize sentences
3) Compute freq(w, class)
4) Get P(w∣pos),P(w∣neg) 
5) Get λ(w)
λ(w)=log(P(w∣pos)/P(w∣neg))
​
6) Compute logprior=log(P(pos)/P(neg))




