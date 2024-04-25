# Earphone Review Classification with Naive Bayes

## Overview
This project implements a Naive Bayes algorithm to classify earphone reviews into positive, neutral, or negative sentiments. It aims to provide insights into customer opinions about earphones based on their reviews.

## Dataset
The dataset consists of earphone reviews collected from Kaggle, each labeled with its corresponding sentiment. It contains a diverse range of opinions and expressions to ensure robustness in classification.

## Preprocessing
The dataset undergoes preprocessing steps including text cleaning, tokenization, stopword removal, and lemmatization to prepare it for model training. These steps help in standardizing and enhancing the quality of textual data.

## Naive Bayes Classifier
The Naive Bayes algorithm is chosen for its simplicity and effectiveness in text classification tasks. It leverages the assumption of conditional independence between features (words) given the class label (sentiment) to make predictions.

## Evaluation
The classification model is evaluated using metrics such as accuracy, tf-idf Score. 

## Usage
1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Execute the preprocessing script `preprocess.py` to clean and preprocess the dataset.
4. Run the training script `train.py` to train the Naive Bayes classifier.
5. Evaluate the trained model using the evaluation script `evaluate.py`.
6. Explore the results and model performance.

## Dependencies
- Python 
- scikit-learn
- NLTK
