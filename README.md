# Social Media Messages in Thai Language Sentimental Analysis
## Overview
This is my first NLP project, which I created to practice my NLP skills by using LSTM model to doing sentimental analysis of social media messages in Thai Language.
## Dataset
The dataset that I used in this project is from PythaiNLP Wisesight Sentiment Corpus:

https://github.com/PyThaiNLP/wisesight-sentiment
## Prerequisites
To run this project, you will need the following libraries:
- Tensorflow/Keras
- Numpy
- Pandas
- Scikit-learn
- Matplotlib     
- Seaborn
- PythaiNlp

## Steps in project
1. Import Necessary Libraries
2. Load Datasets: Load the training, validation, and test datasets from their respective files.
3. Exploratory Data Analysis (EDA): Conduct a thorough exploratory data analysis to understand the characteristics of the data and identify patterns.
4. Preprocessing Text Data: Remove stopwords and perform tokenization to prepare the text data for further analysis.
5. Word Cloud Generation: Create word clouds of the most frequently occurring positive and negative words in the dataset.
8. Data Preparation for LSTM Model: Prepare the dataset for the LSTM model by padding sequences to ensure consistent input shapes.
9. Model Training and Evaluation (LSTM): Train and evaluate an LSTM model to predict sentiment.
10. Testing with Input Text: Test the trained model with some input text.
