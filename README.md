[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/Sj1cBxq-)
This repository is where you should submit your ***code*** for the class Kaggle competition, if you choose that option for your term assignment.

# Introduction

This repository contains a Python script for a text classification task using machine learning algorithms. The script uses the Pandas library for data manipulation, the NLTK library for text preprocessing, and scikit-learn library for machine learning. The purpose of this script is to classify text data into different categories.


# Task

Remember that the backstory and data are described on [the blog site for this task](https://uazhlt-ms-program.github.io/ling-539-course-blog-Spr2023/assignments/class-competition). Your results should be uploaded to the Kaggle task page, which is also where you'll see the class results:

https://www.kaggle.com/competitions/statistical-nlp-spring-2023-class-competition

In order to be added to this competition, you'll need to accept the invitation at this link:

https://www.kaggle.com/t/1e136bfde9a148dab9956b2be1858fda

# Dataset 

The script is designed to work with a text classification dataset in CSV format. The dataset should contain two columns: "TEXT" and "LABEL". The "TEXT" column contains the text data and the "LABEL" column contains the category labels. The train and test datasets should be separate CSV files.

# Code 

The Python script contains four classes:

DataLoader: loads the train and test data from CSV files.
Preprocessor: preprocesses the text data by removing stop words, punctuation, and stemming the words.
FeatureExtractor: extracts features from the preprocessed text data using the TfidfVectorizer.
Classifier: trains and evaluates two classifiers: Naive Bayes and Logistic Regression.
The main function of the script loads the data, preprocesses it, extracts features, and trains and evaluates the classifiers. It then makes predictions on the test data using the best classifier and saves the predictions to a CSV file in the correct format.

# Results 

The script trains and evaluates two classifiers: Naive Bayes and Logistic Regression. The accuracy of the classifiers is printed to the console. The predictions for the test data are saved to a CSV file in the correct format.

# Conclusion 
This Python script provides a framework for a text classification task using machine learning algorithms. It can be easily adapted to work with different datasets and can be extended to include more sophisticated algorithms and features.

# Notes
- You should approach this task **fairly** and with the mindset that you would use to approach a real-world problem. Your goal is to handle the nuances of this data well, while also not over-fitting. Designing a tool that gets a perfect score on training data, while performing poorly on novel data, is not something that would make an employer want to hire you.
- You are not obligated to use Python.
- You may delete or alter any files in this repository.
- You are free to add dependencies. (...but if I can't run it, I may not be able to offer much helpful feedback.)
  - Ensure that your code can be installed/used on another machine running Linux or MacOS (consider containerizing your project with Docker or an equivalent technology).
