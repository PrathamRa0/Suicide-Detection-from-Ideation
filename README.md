# Suicide Detection from Ideation

Main codefile: Webscraper.py
[link to saved Word2vec model not uploaded due to size limits](https://drive.google.com/drive/folders/1kQwjiMsve8nV54Ic0he0LysqK2GS_arj?usp=sharing)

link to dataset:

## Abstract
Suicide is considered a low baseline behavior, which makes it challenging to predict. More than 700,000 people commit suicide each year. Reddit can be a good asset to detect the signs of suicide in a faster and more effective way thanks to the speed of information disseminated through it. By using machine learning and text analysis models, we examined how to predict suicide risk from written communications in an effort to advance suicide prediction and prevention. Specifically, we used a dataset
consisting of more than 2,00,000 unique posts from “Suicide” subreddit on the Reddit Platform

## Description
Our project runs a live webscraper on the r/SuicideWatch subreddit and identifies the following from any new posts-
1. Username
2. Title
3. Content

Considering the Title and Content, we pass the text to a Word2vec vectoriser and then to a Multi layer perceptron model to get classification. In case the text is classified as suicidal, the text is run through the Happy Transformer model to detect the severity of the observed text to enable assignment of priority

## How to use


