# Stock_Sentiment_Analysis
Stock_Sentiment_Analysis_Using_TOP_25_News_Headlines

## Project Overview
This project aims to perform stock sentiment analysis using the top 25 news headlines from a dataset. By analyzing the sentiment of these headlines, the model can determine the overall market sentiment, aiding in investment decision-making.
This project effectively uses a Random Forest Classifier to analyze stock sentiment based on news headlines. The model achieved an accuracy of 84%, indicating its reliability in predicting market sentiment.

## Data Preparation and Cleaning
1. **Loading the Data**: The data is loaded from a CSV file.
2. **Splitting the Data**: The data is split into training and testing sets based on the date.
3. **Cleaning the Data**: Punctuations are removed, and all text is converted to lowercase.
4. **Renaming Columns**: Column names are renamed for ease of access.

## Feature Extraction using Bag of Words
The project employs the Bag of Words technique with bigrams, implemented using `CountVectorizer`, to transform textual data into numerical features suitable for machine learning models.

## Model Training with Random Forest Classifier
A Random Forest Classifier, trained on the processed dataset, is used to classify the sentiment of the news headlines. The classifier is set up with 200 trees and uses entropy as the criterion for information gain.

## Evaluation and Results
The model achieves an accuracy of approximately 84% on the test dataset. Evaluation metrics such as confusion matrix, precision, recall, and F1-score indicate strong performance, especially in identifying both positive and negative sentiments accurately.
