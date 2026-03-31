# Customer Review Sentiment Analysis

This project performs sentiment analysis on customer reviews. It classifies reviews as **positive**, **neutral**, or **negative** using a Bidirectional LSTM model with text preprocessing and stemming.

## Data set
Since the file is too large, Here is the drive link to access the dataset.
https://drive.google.com/file/d/1QN9vs72AVBKcpyj6gHyJZb2QNGedgd9j/view?usp=sharing

## Features

- Preprocesses text by cleaning and stemming words
- Converts review text into sequences using a tokenizer
- Uses an Embedding layer and Bidirectional LSTM for sentiment prediction
- Classifies reviews into three categories: negative, neutral, positive
- Outputs a dataframe with review text and predicted sentiment

## Tech Stack

- Python
- Pandas, Numpy
- NLTK (for stemming)
- TensorFlow / Keras (for model building)
- Scikit-learn (for tokenization and preprocessing)

## Usage

1. Load your dataset containing customer reviews with a `Score` column.
2. Apply sentiment labeling:

