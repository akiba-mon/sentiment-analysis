# Interpretable Social Media Sentiment Classification

MSc Data Science Dissertation Project 
University of South Wales  

## Project Overview
This project investigates the effectiveness of traditional machine learning techniques for sentiment classification on social media text. The objective was to develop an efficient, scalable, and interpretable sentiment analysis framework capable of handling noisy Twitter data while maintaining strong predictive performance.

The study uses the Sentiment140 dataset containing approximately 1.6 million labelled tweets and evaluates multiple machine learning models using TF-IDF feature extraction.

## Dissertation
Full MSc Dissertation (PDF):  
docs/Dissertation.pdf

#### Title: An Efficient and Interpretable Framework for Social Media Sentiment Classification Using Traditional Machine Learning Techniques

## Dataset

Dataset used:
Sentiment140
Approximately 1.6 million tweets
Binary sentiment classification (positive and negative)

source: 
https://www.kaggle.com/datasets/kazanova/sentiment140

## Preprocessing Techniques

The preprocessing pipeline includes:
- Lowercase conversion
- URL replacement
- Username masking
- Emoji translation
- Stopword removal
- Tokenisation
- Text normalisation
- Lemmatisation
- Negation handling

## Feature Engineering

TF-IDF Vectorisation

Configuration:
- Unigrams and Bigrams
- max_features = 500000
- max_df = 0.9
- min_df = 5
- sublinear_tf = True

## Machine Learning Models

The following models were implemented and evaluated:
- Bernoulli Naive Bayes
- Multinomial Naive Bayes
- Logistic Regression
- Linear Support Vector Classifier
- Stochastic Gradient Descent Classifier

## Results

| Model | Test Accuracy |
|---------|---------|
| Bernoulli Naive Bayes | 79.67% |
| Multinomial Naive Bayes | 80.32% |
| SGD Classifier | 77.37% |
| Linear SVC | 81.48% |
| Logistic Regression | 82.60% |

## Best Model

#### Logistic Regression

Reasons:
- Highest test accuracy
- Strong generalisation performance
- Computational efficiency
- High interpretability

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- WordCloud


## License

MIT License
