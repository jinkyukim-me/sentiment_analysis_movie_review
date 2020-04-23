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
<p><img src="https://imagizer.imageshack.com/img922/3107/rKYt4J.jpg" width="100%"></p>

### Lexical Dispersion Plot
<p><img src="https://imagizer.imageshack.com/img923/7671/rDu5lf.jpg" width="100%"></p>

### Wordcloud
<p><img src="https://imagizer.imageshack.com/img922/6622/7z4d51.jpg" width="100%"></p>

## Result
According to result data, top accuracy has shown on Train Step 8. (87.59%)
<p><img src="https://imagizer.imageshack.com/img921/301/bPXne0.jpg" width="100%"></p>
<p><img src="https://imagizer.imageshack.com/img922/6334/XCtOnz.jpg" width="100%"></p>

## Test
<p><img src="https://imagizer.imageshack.com/img922/7098/2QcngR.jpg" width="100%"></p>

## Conclusion
On the model and summarizing the estimated performance. We can see that this model achieves an accuracy of 87.59%. Again, there is a lot of opportunity for further optimization, such as the use of deeper and/or larger layers.
