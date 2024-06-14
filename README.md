# About Fake News Detection Project

## Video link on youtube

## Problem Definition
Develop a machine learning program to identify when a news source may be producing fake news. We aim to use a corpus of labeled real and fake news articles to build a classifier that can make decisions about information based on the content from the corpus. The model will focus on identifying fake news sources, based on multiple articles originating from a source. Once a source is labeled as a producer of fake news, we can predict with high confidence that any future articles from that source will also be fake news. Focusing on sources widens our article misclassification tolerance because we will have multiple data points coming from each source.

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
