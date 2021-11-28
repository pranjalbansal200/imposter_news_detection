# fake_news_detection_mini_project


## Overview

The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable. Our project aims to use Natural Language Processing to detect fake news directly, based on the text content of news articles.

## Problem Definition

Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake new articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news. Focusing on sources widens our article misclassification tolerance, because we will have multiple data points coming from each source.

The intended application of the project is for use in applying visibility weights in social media. Using weights produced by this model, social networks can make stories which are highly likely to be fake news less visible.

## Prerequisites

What things you need to install the software and how to install them:

Python 3.6'

- This setup requires that your machine has python 3.6 installed on it. you can refer to this url https://www.python.org/downloads/ to download python. Once you have python downloaded and installed, you will need to setup PATH variables (if you want to run python program directly, detail instructions are below in how to run software section). To do that check this: https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/.

- Setting up PATH variable is optional as you can also run program without it and more instruction are given below on this topic.

Second and easier option is to download anaconda and use its anaconda prompt to run the commands. To install anaconda check this url https://www.anaconda.com/download/

You will also need to download and install below 3 packages after you install either python or anaconda from the steps above

- Sklearn (scikit-learn)

- numpy

- scipy

if you have chosen to install python 3.6 then run below commands in command prompt/terminal to install these packages
```
pip install -U scikit-learn

pip install numpy

pip install scipy
```

if you have chosen to install anaconda then run below commands in anaconda prompt to install these packages
```
conda install -c scikit-learn

conda install -c anaconda numpy

conda install -c anaconda scipy
```

## The Data

The data comes from Kaggle, you can download it here:

https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset

There are two files, one for real news and one for fake news (both in English) with a total of 23481 "fake" tweets and 21417 "real" articles.

