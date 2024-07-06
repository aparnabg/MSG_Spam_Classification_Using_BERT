# MSG_Spam_Classification_Using_BERT
Repository for classifying spam MSG using BERT with preprocessed dataset and training scripts.



## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)

## Introduction

Classifying SMS messages as spam or not spam is crucial for improving communication efficiency and preventing unsolicited messages. This project leverages the power of BERT (Bidirectional Encoder Representations from Transformers) to effectively classify SMS messages based on their textual content.

## Dataset

The dataset used is the SMS Spam Collection, a set of SMS tagged messages collected for SMS spam research. It contains 5,574 SMS messages in English, tagged as either ham (legitimate) or spam. The dataset is sourced from Kaggle.

## Model Architecture

The model is built using TensorFlow and Keras, with the following architecture:

- Input Layer: Takes in the raw text data.
- BERT Preprocessing Layer: Prepares the input text for BERT encoding.
- BERT Encoder Layer: Generates contextual embeddings for the input text.
- Dropout Layer: Regularizes the model to prevent overfitting.
- Dense Layer: Outputs the final classification.

## Result

The model achieved an accuracy of 92%.