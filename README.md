# Deep_-learning
Sentiment Analysis for Amazon Appliances Reviews.
This project involves performing sentiment analysis on a dataset containing reviews of appliances sold on Amazon. The objective is to classify the sentiment of the reviews into positive or negative sentiments using a binary classification approach.

Dataset:
Description
The dataset used for this project contains reviews of various appliances obtained from Amazon. Each review consists of text data and a corresponding sentiment label (positive or negative).

Source
The dataset was retrieved from [https://jmcauley.ucsd.edu/data/amazon/].

Structure
The dataset includes the following columns:
overall,verified,reviewTime,reviewerID,asin,style,reviewerName ,reviewText,summary ,unixReviewTime,vote,image.  

Review Text: Textual data containing the review content.
Sentiment Label: Indicates the sentiment of the review (Positive or Negative).
Methodology
Tools Used
TensorFlow: Used for building and training the sentiment analysis model.
DistilBERT Model: Leveraged a pre-trained DistilBERT model for transfer learning and NLP tasks.
NumPy and Pandas: Utilized for data manipulation, preprocessing, and analysis.
Model Development

The sentiment analysis model was developed using TensorFlow with a transfer learning approach. The DistilBERT model served as the foundation for the sentiment classification task.

Project Structure
Files
sentiment_analysis.ipynb: Jupyter Notebook containing the code for data preprocessing, model development, and evaluation.

Requirements
Python 3
TensorFlow
Pandas
transformers
NumPy
