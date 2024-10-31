# Sentiment-Analysis-of-Movie-Reviews
This project aims to classify movie reviews as either positive or negative using deep learning. By leveraging **natural language processing (NLP)** and a dataset from **Kaggle**, we developed a model that predicts the sentiment of a review. 

## Project Overview
The model is trained on movie reviews, using NLP techniques to preprocess text data and deep learning techniques to classify sentiments. Our approach focuses on creating an embedding representation of text, followed by training an LSTM model to capture contextual sentiment. 

## Libraries Used 
 * os and zipfile for file handling and data extraction 
 * pandas for data manipulation 
 * sklearn for splitting data 
 * tensorflow for building and training the model 
 * NLP tools: Tokenizer, pad_sequences for text preprocessing 
 * Embedding and LSTM layers for deep learning architecture

## Model Overview
The model architecture includes: 
1. **Embedding Layer** - Converts words into dense vectors of fixed size.
2. **LSTM Layer** - Captures long-term dependencies in text sequences.
3. **Output Layer** - Classifies the review sentiment.

## Results 
The trained model achieves a classification accuracy for predicting the sentiment of movie reviews. After training and testing, the model can effectively distinguish between positive and negative sentiments based on review text, providing valuable insights for analyzing large sets of movie-related comments. This approach can be adapted for sentiment analysis in other domains as well.
