**Spam Email Detection Using Machine Learning**

**Overview**

This project aims to build a machine learning model capable of detecting spam emails using the SMS Spam Collection Dataset . The model uses text preprocessing techniques and a Naive Bayes classifier to classify emails as either "spam" or "ham" (not spam). The goal is to create an accurate and efficient system for filtering out unwanted spam messages.

**Problem Statement**

Unwanted spam emails clutter inboxes, waste time, and may even contain malicious content that threatens security. Traditional rule-based systems often fail to catch sophisticated spam schemes, leading to financial losses and customer dissatisfaction. The challenge is to develop an automated system that can accurately classify incoming emails as "spam" or "ham" based on their content.

**Dataset**

The dataset used in this project is the SMS Spam Collection Dataset , which contains 5,572 SMS messages labeled as either "spam" or "ham". It is a publicly available dataset from the UCI Machine Learning Repository .

Features : Text content of the messages.
Target Variable : Label (spam or ham).
Distribution :
Ham: 4,825 messages (86.6%)
Spam: 747 messages (13.4%)

**Methodology**

The project follows these steps:

Data Loading : Load the dataset from a remote URL or local file.
Data Exploration : Analyze the structure and distribution of the dataset.
Data Preprocessing :
Clean the text data by removing special characters, converting to lowercase, and stemming words.
Remove stopwords (common words like "the," "and").
Feature Extraction : Convert the cleaned text into numerical features using TF-IDF vectorization.
Train-Test Split : Split the dataset into training and testing sets (80% train, 20% test).
Model Development : Train a Multinomial Naive Bayes classifier on the training data.
Model Evaluation : Evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.

**Results**

The model achieved the following performance metrics on the test set:

Accuracy : ~98%
Precision : ~96%
Recall : ~93%
F1-Score : ~94%
These results indicate that the model is highly effective at distinguishing between spam and ham emails.
