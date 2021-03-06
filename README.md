# Sarcasm Detection using Reddit Comments Dataset
A group project for module CS3244 Machine Learning 2021 Semester 1. Obtained top 25% among all the projects.

## Project Breakdown
- Perform data cleaning and feature extraction on the datasets
- Train baseline models
  - Use manually selected features, TF-IDF vectors, and a hybird of both as inputs
  - Baseline models include Naive Bayes, Logistic Regression, and Support Vector Machine
- Train Convolutional Neural Network (CNN) model with Keras embeddings as inputs
- Perform microscopic and macroscopic analysis on the model performance
- Use Local Interpretable Model-agnostic Explanations (LIME) technique for both numeric (for manually selected features) and text inputs to analyse impacts of words to prediction results.

## Dataset
The dataset is from Kaggle: [Sarcasm on Reddit](https://www.kaggle.com/danofer/sarcasm)

## References
<a id="1">[1]</a> 
Sundararajan, K., & Palanisamy, A. (2020).
Multi-rule based ensemble feature selection model for sarcasm type detection in Twitter.


<a id="2">[2]</a> 
Sarsam, S. M., et. al. (2020).
Sarcasm detection using machine learning algorithms in Twitter: A systematic review.

<a id="3">[3]</a> 
Poria, S., Cambria, E., Hazarika, D., Vij, P. (2017).
A Deeper Look into Sarcastic Tweets Using Deep Convolutional Neural Networks.