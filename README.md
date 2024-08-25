# CodeAlpha_IMAGE-RECOGNITION
Task 1: Image Recognition
Overview
This project demonstrates image recognition using TensorFlow and the MNIST dataset. Image recognition involves analyzing digital images to classify objects, such as handwritten digits in this case.
What I Did:
Dataset Loading and Exploration: Loaded and explored the MNIST dataset of 28x28 pixel grayscale images of digits (0-9).
Model Building: Created a neural network model with:
A Flatten layer
A Dense layer with 128 units and ReLU activation
A final Dense layer with 10 units for classification
Model Compilation: Compiled with Adam optimizer and sparse categorical crossentropy loss.
Training: Trained the model for 10 epochs, achieving high accuracy.
Evaluation: Tested the model, obtaining a test accuracy of approximately 93.35%.
Prediction and Visualization: Made predictions and visualized results to compare actual and predicted labels.
Results
Training Accuracy: ~95.57%
Test Accuracy: ~93.35%
#CODEALPHA_TWITTER_SENTIMENT
Twitter Sentiment Analysis using LSTM
This repository contains a Twitter Sentiment Analysis project implemented using an LSTM neural network in TensorFlow/Keras. The project classifies tweets into four categories: Positive, Neutral, Negative, and Irrelevant.

Overview
Data: The dataset contains over 74k tweets with their associated sentiments.
Model: An LSTM model with regularization and dropout layers to prevent overfitting.
Preprocessing: Tokenization and padding of tweet sequences to prepare the data for the LSTM model.
Visualization: Sentiment distribution visualized using bar graphs and pie chart
