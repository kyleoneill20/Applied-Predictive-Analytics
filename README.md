# Applied-Predictive-Analytics
K Nearest Neighbors for IMDB Movie Review Sentiment Analysis

This project implements a K Nearest Neighbors (KNN) model to classify the sentiment of movie reviews from the IMDB Movie Review Dataset. The dataset contains labeled reviews, with 1 indicating a positive sentiment and 0 indicating a negative sentiment. The goal of this project is to experiment with different preprocessing techniques and hyperparameters to build an effective sentiment classification model.

Key Features:
Dataset Preprocessing: Used TfidfVectorizer and CountVectorizer for text vectorization, with binary options and varying feature sizes.
KNN Model: Trained a KNN classifier and optimized it by experimenting with different numbers of neighbors (n_neighbors).
Performance Metrics: Evaluated models using accuracy and weighted F1-score on the test dataset.
Experimentation: Tested various parameters such as max_features and binary settings for vectorizers to identify the best configuration.
This repository contains the code for reading the dataset, training and testing the KNN model, and conducting extensive experimentation to achieve optimal performance.
