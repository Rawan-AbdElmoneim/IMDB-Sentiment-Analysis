# IMDB Sentiment Analysis

## Overview
This project uses LSTM (Long Short-Term Memory) networks to perform sentiment analysis on IMDB movie reviews, predicting whether a review is positive or negative based on its text content.

## Dataset
The dataset consists of 50,000 labeled movie reviews (25k positive, 25k negative) from the IMDB Dataset on Kaggle.

## Tools and Libraries Used
- Python
- Pandas
- NLTK
- TensorFlow
- Keras

## Preprocessing
- Text cleaning: Removal of HTML tags, punctuation, and non-alphanumeric characters.
- Normalization: Lowercasing, tokenization, stopword removal, lemmatization, and stemming.

## Model Architecture
- Embedding Layer: Converts text inputs into dense vectors.
- LSTM Layer: Handles sequence data with dropout for regularization.
- Dense Layers: Final layers for classification.

## Training and Evaluation
- Split dataset into training (80%) and testing (20%).
- Compiled with binary cross-entropy loss and Adam optimizer.
- Achieved accuracy of [insert accuracy score] on the test set.

## Sample Predictions
- "Disappointing plot and dull performances" --> Negative
- "Masterpiece, captivating from beginning to end!" --> Positive


