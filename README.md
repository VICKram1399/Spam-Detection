# Spam-Detection
text classification model for spam detection

## Project Overview

The goal of this project is to provide a foundational example of how to build a text classification model for spam detection. It uses a bag-of-words approach for feature representation and the Naive Bayes algorithm, which is known for its effectiveness in text categorization tasks.

## Model Training and Evaluation
### Preprocessing:
Email text is cleaned (converted to lowercase, punctuation removed).
Stop words are removed (common words like "the," "and").
Stemming is applied to reduce words to their base form.

### Feature Extraction:
A bag-of-words model is used to convert text into numerical features.
Model Training:

A Naive Bayes model is trained on the preprocessed data.

### Evaluation:
The model is evaluated on a test set using metrics like accuracy, precision, recall, and F1-score.


