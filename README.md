# SENTIMENT ANALYSIS ON NAVER MOVIE DATASET

## Overview
Sentiment Analysis is used to discover people’s opinions, emotions and feelings about a product or service.
This model will try to predict the sentiment of the movie reviews with positive or negative. 

## Problem
The problem is to determine whether the given movie review has a positive or negative sentiment.

## Dataset
Dataset used in this problem is [NAVER Review Dataset](https://github.com/e9t/nsmc/). It contains 200,000 movie reviews( positive or negative) for original, 150,000 movie reviews( positive or negative) for training and 50,000 movie reviews( positive or negative) for testing.

## Requirement
* Python 3.6
* Pytorch 1.2
* KoNLPy
* Mecab
* nltk
* matplotlib
* numpy
* wordcloud

## Data Exploration

### Words
<p><img src="https://github.com/jinkyukim-me/sentiment_analysis_movie_review/blob/master/img/graph_word.JPG" width="100%"></p>

### Lexical Dispersion Plot
<p><img src="https://github.com/jinkyukim-me/sentiment_analysis_movie_review/blob/master/img/lexical_dispersion_plot.JPG" width="100%"></p>

### Wordcloud
<p><img src="https://github.com/jinkyukim-me/sentiment_analysis_movie_review/blob/master/img/wordcloud.JPG" width="100%"></p>

### Result
According to result data, top accuracy has shown on Train Step 8.
<p><img src="https://github.com/jinkyukim-me/sentiment_analysis_movie_review/blob/master/img/training1.JPG" width="100%"></p>
<p><img src="https://github.com/jinkyukim-me/sentiment_analysis_movie_review/blob/master/img/training2.JPG" width="100%"></p>

## Conclusion
On the model and summarizing the estimated performance. We can see that this model achieves an accuracy of 87.59%. Again, there is a lot of opportunity for further optimization, such as the use of deeper and/or larger layers.
