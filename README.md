# Sentiment Analysis of Chat Messages using NLP and Deep Learning

## Overview

This project classifies chat messages into different sentiment categories using Natural Language Processing (NLP) and Machine Learning techniques. The project compares a traditional machine learning approach (Logistic Regression with Bag of Words) against a Deep Learning approach (LSTM with Word Embeddings).

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

## Dataset

The dataset contains chat messages labeled with sentiment classes. Each message undergoes preprocessing before being used for model training and evaluation.

## Project Workflow

### 1. Data Preprocessing
- Converted text to lowercase
- Removed URLs and special characters
- Tokenization
- Stopword removal
- Lemmatization

### 2. Exploratory Data Analysis
- Sentiment distribution analysis
- Word frequency analysis
- Word length distribution by sentiment

### 3. Feature Engineering

#### Logistic Regression Model
- Bag of Words representation using CountVectorizer

#### LSTM Model
- Tokenization
- Sequence conversion
- Padding
- Word Embedding layer

### 4. Model Training

#### Model 1: Logistic Regression
- CountVectorizer
- Logistic Regression classifier

#### Model 2: LSTM Neural Network
- Embedding Layer
- LSTM Layer
- Dropout Layer
- Dense Output Layer

### 5. Evaluation Metrics
- Accuracy Score
- Classification Report
- Validation Accuracy
- Model Comparison

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression (Bag of Words) | 82% |
| LSTM with Word Embeddings | 44% |

In this dataset, the Logistic Regression model outperformed the LSTM model. The results suggest that traditional machine learning methods can be highly effective for sentiment classification, especially when working with limited datasets. The project provides a practical comparison between conventional NLP techniques and deep learning approaches.

## Key Learning Outcomes

- Natural Language Processing fundamentals
- Text preprocessing techniques
- Feature extraction using Bag of Words
- Deep learning for text classification
- Model evaluation and comparison
- Data visualization

## Future Improvements

- TF-IDF feature extraction
- Pre-trained word embeddings (Word2Vec, GloVe)
- Transformer-based models (BERT)
- Streamlit deployment for real-time predictions

