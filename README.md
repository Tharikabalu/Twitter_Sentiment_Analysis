# Twitter_Sentiment_Analysis
Classification of tweets into either positive or negative sentiments. This repository includes implementations of two machine learning algorithms for binary classification: 
* Logistic Regression  
* Naive Bayes<br>
<br>**Logistic Regression: Training**<br>
<br>To train your logistic regression function, you will do the following:<br>
<img width="705" alt="lr1" src="https://github.com/Tharikabalu/Twitter_Sentiment_Analysis/assets/91038929/178f1b85-e1ad-4941-b334-91f3ee7e137b"><br>
You initialize your parameter θ, that you can use in your sigmoid, you then compute the gradient that you will use to update θ, and then calculate the cost. You keep doing so until good enough.
Usually you keep training until the cost converges. If you were to plot the number of iterations versus the cost, you should see something like this:<br>
<img width="1117" alt="lr2" src="https://github.com/Tharikabalu/Twitter_Sentiment_Analysis/assets/91038929/17ec8e89-4e22-4b00-a9de-c23b6af68a4d">
<br>**Training naïve Bayes**<br>
<br>To train your naïve Bayes classifier, you have to perform the following steps:<br>
1) Get or annotate a dataset with positive and negative tweets
2) Preprocess the tweets: process_tweet(tweet) ➞ [w1, w2, w3, ...]:
* Lowercase
* Remove punctuation, urls, names
* Remove stop words
* Stemming
* Tokenize sentences
3) Compute freq(w, class)
4) Get P(w∣pos),P(w∣neg) 
5) Get λ(w)
λ(w)=log(P(w∣pos)/P(w∣neg))
6) Compute logprior=log(P(pos)/P(neg))




