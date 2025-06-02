# fakenews

# AI-Based Fake News Detection and News Categorization

This project presents an AI-powered system designed to combat the spread of misinformation and improve news accessibility. It integrates two deep learning models—one for fake news detection using a BiRNN-MLP hybrid and another for news categorization using the transformer-based DistilBERT model. A user-friendly interface built with Tkinter allows seamless interaction for real-time analysis.

## Project Overview

The project offers a dual-solution system:

- Fake News Detection using a BiRNN-MLP hybrid model
- News Categorization using DistilBERT, a transformer-based NLP model

The models are integrated into a Python-based GUI, making it accessible for non-technical users to analyze news articles in real time.

## Features

- Detects whether a news article is real or fake with 95.44% accuracy
- Classifies articles into 7 categories with 95.12% accuracy:
  - Politics
  - Sports
  - Entertainment
  - World
  - Science
  - Technology
  - Automobile
- GUI implemented using Tkinter
- Preprocessing includes tokenization, stopword removal, stemming, and lemmatization

## Datasets Used

- Fake News Dataset: Indian Fake News dataset from Kaggle (Real: 1,877 | Fake: 1,852)
- News Category Dataset: Articles categorized into 7 domains

## Models Used

### BiRNN-MLP (Fake News Detection)

- Bidirectional Recurrent Neural Network (BiRNN) captures context in both directions
- Multi-Layer Perceptron (MLP) performs binary classification
- Accuracy: 95.44%

### DistilBERT (News Categorization)

- Fine-tuned for multi-class classification using Hugging Face Transformers
- Accuracy: 95.12%

## Tech Stack

- Python 3.x
- TensorFlow and Keras
- Hugging Face Transformers
- Scikit-learn
- Tkinter
- Matplotlib and Seaborn

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## GUI Overview

The application includes:

1. Welcome Page
2. Task Selection Page
3. Input Page for news content
4. Result Page showing prediction and category

## Performance Summary

| Task                 | Accuracy | Model        |
|----------------------|----------|--------------|
| Fake News Detection  | 95.44%   | BiRNN-MLP    |
| News Categorization  | 95.12%   | DistilBERT   |

