# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Capstone : Sentiment analysis for curfew in Saudi Arabia

<img src="https://www.al-khaleeg.com/wp-content/uploads/2020/04/IMG-20200420-WA0157.jpg" style="height: 350px; width: 900px">




This is project for Data Science Immersive course from General Assembly.

## Table of contents
* [Problem Statement](#Problem-Statement)
* [Datasets Description](#Datasets-Description)
* [Data Dictionary](#Data-Dictionary)
* [The Capstone Notbooks](#capstone-Notbook)
* [Conclusions](#Conclusions)
* [Reference](#Reference)
* [Group Members](#Group-Members)


## Problem Statement <a name="Problem-Statement"></a>

During this curfew, people used the social media such as Twitter to express their feelings and find a way to calm themselves down and to feel that they are connected. In our capstone, we will analyze the tweets that are related to COVID19 from hashtags populated from Saudi Arabia. This analysis will analyze how the people on Saudi Arabia are dealing with the situation and the procedures set by the government.



## Datasets Description <a name="Datasets-Description"></a>

The dataset used in this project collected by Dr. Aseel Addawood

* [Coronavirus: Public Arabic Twitter Dataset](https://github.com/aseelad/Coronavirus-Public-Arabic-Twitter-Data-Set/)
in this project we couln't uploads all the datasets that we used from the very first step due to the hugeness of the data
so we only upload the final dataset that we combine all the tweets that we cleaned and applied the machine learning models to it.




##  Data Dictionary <a name="Data-Dictionary"></a>

The dataset's features listed bellow:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|Id|int|df|Id of the tweet|
|created_at|object|df|the time the tweet is published |
|full_text|object|df|the contect of the tweet|
|location|object|df|the user's location|
|sntiment|object|df|the classification of the tweet positive/ negative/ neutral|

##  The Capstone Notbook <a name="capstone-Notbook"></a>

In this Capstone we divided the work into 3 notbook. the first notebook (sentiment Analysis - part one) it contain
the codes for openenig the files and merged it into one dataset. the Second notbook (Extract the data by hashtags - part two) in contain extracting the tweets based one specific hashtags. The third notebook (EDA and Modeling - part three) it has the cleaning part, EDA and the Machine learning.

## Conclusions <a name="Conclusions"></a>

After Data cleaning(EDA), we want to train the models to classfy the tweets in to Positive, negative or spam tweets, and with this kind of data we used different classification models like Linear, LogisticRegression, Naive Bayes)MultinomialNB)., SGDClassifier, PassiveAggressiveClassifier and RidgeClassifier, but the best result was with the LogisticRegression model which have achieved a 0.780 test score.



## Reference <a name="Reference"></a>

Bellow are some References that we used for the capstone
* [twitter sentiment extaction analysis](https://www.kaggle.com/tanulsingh077/twitter-sentiment-extaction-analysis-eda-and-model)
* [sentiment analysis-of tweets in russian](https://github.com/sismetanin/sentiment-analysis-of-tweets-in-russian/blob/master/Sentiment%20Analysis%20of%20Tweets%20in%20Russian%20using%20Multinomial%20Naive%20Bayes.ipynb)
* [extracting twitter data pre-processing](https://towardsdatascience.com/extracting-twitter-data-pre-processing-and-sentiment-analysis-using-python-3-0-7192bd8b47cf)
* [multi class text classification model](https://towardsdatascience.com/multi-class-text-classification-model-comparison-and-selection-5eb066197568)
* [multiclass classification in python](https://setscholars.net/2019/02/10/how-to-classify-wine-using-sklearn-linear_models-multiclass-classification-in-python/)


## Group Members <a name="Group-Members"></a>

* [Najwa Alharbi](https://www.linkedin.com/in/najwa-sayyaf-alharbi/)
* [Fatimah Aljohani](https://www.linkedin.com/in/fatmah-aljohani/)
* [Rawan Almalki](https://www.linkedin.com/in/rawan-almalki/)
