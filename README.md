# Twitter Arabic Sentiment Analysis

## Overview: 
Perform Arabic sentiment analysis on tweets using NLTK and classifies them by content if the person is a fan of Real Madrid FC or Barcelona FC.

## Approach:
* Imported dataset
* Clean data
* Analysed data
* Used Count Vectorizer
* Prediction using SGDClassifier
* Prediction using MLPClassifier
* Prediction using Multinomial Naive Bayes 
* Applied Grid Search Cross Validation
* Comparison between various classifier

## Conclusion:
Best accuracy comes from SGDClassifier : 70%.

## Example:
    "افضل فريق في الدوري هو برشلونة" - true value : B - output value : B
    "البرشا و بس و الباقي خس" -  true value : B - output value : R
    "النادي الملكي عشقي" -  true value : R - output value : R
    "متعة كرة القدم عند مشاهدة مباراة للريال ❤" -  true value : R - output value : R
    "برشلونة لا حدى يعلى عليه" -  true value : B - output value : B
    "الدوري مابينشاف بلا ميسي و برشلونة" -  true value : B - output value : B
    "الله على الكتلاااان" -  true value : B - output value : B


