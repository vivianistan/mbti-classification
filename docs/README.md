# MBTI Classification

> Using this dataset: https://www.kaggle.com/datasnaek/mbti-type 

Team members: Bianca Antonio, Chethan Valleru, Connor Byron, [Gopika Ajaykumar](https://github.com/gopikaajaykumar) (INFP), James Park, [Vivian Tan](https://vivianistan.github.io/) (INTJ) 


* [Code](https://github.com/vivianistan/mbti-classification)

* [Site](https://github.com/vivianistan/mbti-classification/#/)

# Context

The Myers Briggs Type Indicator (or MBTI for short) is a personality type system that divides everyone into 16 distinct personality types across 4 axis:

* Introversion (I) – Extroversion (E)
* Intuition (N) – Sensing (S)
* Thinking (T) – Feeling (F)
* Judging (J) – Perceiving (P)

You can learn more about what these mean [here](http://www.myersbriggs.org/my-mbti-personality-type/mbti-basics/home.htm?bhcp=1) or [here](https://www.16personalities.com/personality-types)

It is one of, if not the, the most popular personality test in the world. It is used in businesses, online, for fun, for research and lots more. A simple google search reveals all of the different ways the test has been used over time. It’s safe to say that this test is still very relevant in the world in terms of its use.

The data was collected through the PersonalityCafe forum, as it provides a large selection of people and their MBTI personality type, as well as what they have written.

This dataset contains over 8600 rows of data, on each row is a person’s:

* Type (This persons 4 letter MBTI code/type)
* A section of each of the last 50 things they have posted (Each entry separated by "|||" (3 pipe characters))

# Goal

The goal of this project is to try to classify a person's MBTI personality type based on the last 50 things they have posted. 

## Approach

We divided this classification problem into 4 subproblems: 

* Classify as E or I
* Classify as S or N
* Classify as F or T
* Classify as J or P

We decided to focus on data cleaning and feature engineering before trying different models. 

Here are some of the features we tried to add: 
 
 * words per comment
 * variance of word counts
 * links per comment
 * images per comment 
 * question marks per comment
 * exclamation marks per comment
 * ellipsis per comment 
 * sentiment
 * number of part of speech tags (didn't implement, took too long)


Here are some models we tried: 

* Xgboost
* Neural Net
* Logistic regression
* Random forest

## Results





