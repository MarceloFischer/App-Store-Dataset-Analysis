# App Store Dataset Analysis
 

## 1. Introduction
This repository has the goal to show a starting analysis done in the App Store dataset collected on August 3rd 2019 from [Kaggle](https://www.kaggle.com/tristan581/17k-apple-app-store-strategy-games) using the [iTunes API](https://affiliate.itunes.apple.com/resources/documentation/itunes-store-web-service-search-api/) and the [App Store sitemap](https://apps.apple.com/us/genre/ios-games/id6014).
  Some questions I'll try to answer are:

    1. Does the advance in technology impact the size of the apps?
    2. Does the advance in technology impact the amount of apps being produced?
    3. Are most apps free or paid and which category is more popular?
    4. Is there a better one between free or paid apps?
    5. How is the distribution of the age restriction?
    6. Do most games offer more than one language?
 
The notebook is written in Python.

## 2. Requirements
In this notebook I make use of the **numpy**, **pandas**, **seaborn** and **matplotlib** modules in Python. The versions I used are:
 - seaborn==0.10.0
 - pandas==1.0.3
 - numpy==1.18.1
 - matplotlib==3.1.3

All of them can be installed via pip3 or conda as follows:

 > conda install <seaborn/pandas/numpy/matplotlib>

Via pip3 (used for Python3):

 > pip3 install <seaborn/pandas/numpy/matplotlib>
 
## 3. Techniques
Some techniques that I used include: get the data, establish questions, omit usless data, visualize the data and answer questions.
 
## 4. Insights
With the advance in technology the apps are able to have better graphics and more features, which results in an increase in the memory space they occupy. The advance in technology and the devices becoming more accessible also showed an increase in the amount of apps released per year, from 2008 to 2016, as more more people were probably using and buying these kind of products. After 2016, the data shows a decreasing behaviour, which I suggest as being a result of overproduction of apps. Analysing the distribution of free and paid apps it is clear that the vast majority of the apps are free. At the same time, free apps offer more in-app purchases, what can be expected as they need other sources of income. Comparing the users' ratings for free and paid apps, no category is better with both showing good ratings overall. Last but no least, most of the games are for 4+ years old and the prefered language is English.