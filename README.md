# About Data Dredge

This project is available for open source contribution

## Overview  
The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable.  Our project aims to use Machine learning algorithms to detect fake news directly, based on the text content of news articles. 

## Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake news articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news. Focusing on sources widens our article misclassification tolerance because we will have multiple data points coming from each source.

The intended application of the project is for use in applying visibility weights in social media. Using weights produced by this model, social networks can make stories that are highly likely to be fake news less visible.

Planning: -
1. Data Collection
2. Model Building
3. Backend work
4. Deployment 

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install library.

```bash
pip install virtualenv
```
```bash
virtualenv env_name
```
```bash
env_name/scripts/activate
```
## Start Project

Follow these commands to start your project.

```bash
pip install -r requirements.txt
```
```bash
python app.py
```


