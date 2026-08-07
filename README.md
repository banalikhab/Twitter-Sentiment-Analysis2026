# Twitter-Sentiment-Analysis2026

A machine learning project that classifies tweets as **Positive** or **Negative** using Natural Language Processing (NLP).

## Overview

The project uses the **Sentiment140 dataset** and follows a standard NLP pipeline:

* Text preprocessing and cleaning
* Stemming using NLTK `PorterStemmer`
* Feature extraction using **TF-IDF**
* Sentiment classification using **Logistic Regression**
* Model evaluation using accuracy

## Technologies

* Python
* Pandas & NumPy
* NLTK
* Scikit-learn
* TF-IDF
* Logistic Regression
* Google Colab

## Dataset

**Sentiment140** — approximately 1.6 million labeled tweets.

## Project Structure

```text
Twitter-Sentiment-Analysis/
├── Twitter_Sentiment_Analysis.ipynb
├── README.md
└── dataset/
    └── sentiment140.csv
```

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Load the Sentiment140 dataset.
3. Run the notebook cells sequentially.
4. Train the model and evaluate its performance.
5. Enter new tweets to predict their sentiment.

## Key Concepts

NLP • Text Preprocessing • Stemming • TF-IDF • Logistic Regression • Sentiment Classification • Model Evaluation

## Future Improvements

* Compare multiple ML algorithms
* Improve text preprocessing
* Handle emojis, hashtags, and slang
* Experiment with deep learning and transformer models
* Deploy the model as a web application

## Disclaimer

This project is intended for educational purposes. Predictions depend on the dataset and model used and may not accurately represent the full context or emotion of a tweet.
