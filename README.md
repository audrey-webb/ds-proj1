# README

### Objective
Use the Twitter API to analyze United States President's tweets. 

#### Tweet Source Analysis 
This aims to understand if there's a difference in his Tweet behavior across devices. 

#### Sentiment Analysis
It turns out that we can use the words in Trump's tweets to calculate a measure of the sentiment of the tweet. 

We will use the VADER (Valence Aware Dictionary and sEntiment Reasoner) lexicon to analyze the sentiment of Trump's tweets. VADER is a lexicon and rule-based sentiment analysis tool that is specifically attuned to sentiments expressed in social media. It gives the sentiment of individual words and contains emojis as well. The first column of the lexicon is the token, or the word itself, and the second column is the polarity of the word, or how positive / negative it is.

The basic idea:
- For each tweet, find the sentiment of each word.
- Calculate the sentiment of each tweet by taking the sum of the sentiments of its words. 

#### Engagement Analysis 
Which words led to a greater average number of retweets? 

#### Polarity and Retweet Count 
Does sentiment affect retweet count? 



We give license for our code to be shared. 
