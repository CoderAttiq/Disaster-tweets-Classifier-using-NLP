# Disaster Tweet Classification using NLP

## Overview
This project builds an end-to-end NLP pipeline to classify tweets as real disaster-related or not. The system is designed to assist emergency response agencies in automatically triaging large volumes of social media data during crisis events.

## Dataset
The dataset consists of tweets labeled as disaster (1) or non-disaster (0), including tweet text, keywords, and location metadata.

## Methodology
- Text preprocessing: lowercasing, regex cleaning, tokenization, stop-word removal, lemmatization
- Feature engineering: Bag-of-Words, TF-IDF (unigrams + bigrams), Word2Vec embeddings
- Models: Multinomial Naïve Bayes, Logistic Regression
- Evaluation: Accuracy, Precision, Recall, F1-score

## Results
Logistic Regression with TF-IDF features achieved the best overall performance, providing a strong balance between recall and precision.

## Reproducibility
All experiments use fixed random seeds. Dependencies are listed in `requirements.txt`.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the notebook from top to bottom.
