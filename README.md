# Fake-news-Detection

## Overview  
Fake news detection on social media has recently become an emerging research that is attracting tremendous attention. From defining fake, biased, and misleading news in the first place to deciding how to take action (a blacklist is not a good answer), there's a lot of information to consider beyond what can be neatly arranged in a CSV file.

## Motivation
  * [Fake news detection : A Data Mining perspective](https://arxiv.org/pdf/1708.01967.pdf)
  * [FAKE NEWS IDENTIFICATION - Stanford CS229](http://cs229.stanford.edu/proj2017/final-reports/5244348.pdf)
  * [Daniel Sieradski's BS Detector](https://github.com/selfagency/bs-detector)

## Problem Definition
Develop a machine learning program to identify when an article might be fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The dataset will be composed of articles and sources. We classify sources as good or bad. Once a source is bad, all articles from that source are bad. We can get an accurate result because a source will put out lots of fake articles, so a small chance of misclassification for each article will be averaged out.  

The intended application of the project is for use in applying visibility weights in social media.  Make stories which are highly likely to be fake news less visible. 
