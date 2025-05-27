# PhishingDetector
A deep learning and NLP project

This project presents a deep learning approach to classify SMS messages as Spam or Ham (Not Spam), using a Bidirectional LSTM (BiLSTM) model. It follows a complete end-to-end pipeline from data preprocessing to model training and evaluation, with clearly commented code for easier understanding.

# Dataset
The dataset used is the SMS Spam Collection Dataset from the UCI Machine Learning Repository. It includes over 5,000 SMS messages labeled as spam or ham.

# Features
- End-to-end text classification pipeline
- Data cleaning and preprocessing
- Tokenisation and padding
- Word embeddings
- Deep learning model with BiLSTM architecture
- Evaluation using accuracy, confusion matrix, and other metrics
- Commented code for clarity and learning


# Why BiLSTM?
Long Short-Term Memory (LSTM) is a type of recurrent neural network (RNN) that is capable of learning long-range dependencies in sequential data. It uses memory cells and gating mechanisms (input, forget, output gates) to retain and control the flow of information, making it especially effective for text and time-series data.

While a regular LSTM processes input sequences in a single direction (typically left to right), BiLSTM processes the data in both forward and backward directions. This is particularly advantageous in natural language tasks because:
- Context can depend on both past and future words in a sentence (e.g., the word “free” might mean something different depending on what follows it).
- BiLSTM captures a more comprehensive understanding of the input by learning from both directions.
- It leads to better classification performance, especially in short and noisy texts like SMS messages.
