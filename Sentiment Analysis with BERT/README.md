# Sentiment Analysis using BERT

## Introduction
This repository contains the code for a sentiment analysis project that aims to classify Indonesian tweets from the 2014 presidential campaign as either positive or negative. The project was completed as part of a class assignment by a team of four members, with my main contribution being the implementation of fine tuning the BERT pretrained model.

## Motivation
Sentiment analysis is a popular application of natural language processing, with many potential real-world applications in areas such as market research, brand management, and public opinion analysis. In Indonesia, sentiment analysis can provide valuable insights into public sentiment during election campaigns, which can inform political strategies and decision-making.

## Data
The dataset used for this project consists of tweets collected during the 2014 presidential campaign in Indonesia. The dataset contains around 1.800 tweets, with each tweet labeled as either positive or negative. The dataset was provided by our lecturer and preprocessed by the team to ensure that the text is clean and ready for analysis.

## Methodology
The BERT (Bidirectional Encoder Representations from Transformers) pretrained model was used as the base model for this sentiment analysis task. BERT is a transformer-based model that is pre-trained on a large corpus of text data, and has achieved state-of-the-art results on many natural language processing tasks.

We fine-tuned the BERT model by adding additional layers on top of it, including a BiLSTM layer for contextualization and an output layer for classification. The model was trained on the labeled tweet dataset using the Adam optimizer, and the hyperparameters were tuned using bayesian optimization. We achieved an accuracy of over 88% on the test set, which is a promising result for this task.