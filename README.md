# News Classification: Fake or True Using Naive Bayes

This project demonstrates how to classify news articles as either fake or true using the Naive Bayes algorithm. The project employs a news dataset consisting of text from news articles and their corresponding labels (fake or true). The goal is to train a Naive Bayes classifier to accurately classify new articles based on their content.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Data](#data)
- [Model and Approach](#model-and-approach)
- [Code Explanation](#code-explanation)
- [References](#references)

## Introduction

Fake news classification is an important task that involves distinguishing between true and fake news articles. In this project, the Naive Bayes algorithm is used to classify news articles as either fake or true based on their textual content.

## Features

- Uses Naive Bayes algorithm for news classification.
- Classifies news articles as either fake or true.
- Can handle a large dataset of news articles.

## Setup and Installation

1. **Clone the Repository**:
    - Clone the project repository to your local machine.
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Create a Virtual Environment**:
    - Create and activate a virtual environment (recommended).
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install Dependencies**:
    - Install the required Python packages using the provided `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the Script**:
    - Run the script to train and evaluate the Naive Bayes model.
    ```bash
    python news_classification.py
    ```

2. **Provide Input**:
    - The script will prompt you to input news articles for classification.
    
3. **Receive Classification**:
    - The system will classify the input news articles as either fake or true.

## Data

- The news dataset used in this project consists of news articles and their labels (fake or true).
- The dataset is used to train and evaluate the Naive Bayes model.

## Model and Approach

- The project employs the Naive Bayes algorithm for classifying news articles.
- The dataset is preprocessed, and features are extracted from the text.
- The Naive Bayes model is trained on the processed data.
- Once trained, the model can classify new news articles as either fake or true.

## Code Explanation

- **news_classification.py**:
    - The script for loading the news dataset, training the Naive Bayes model, and evaluating its performance.
    - Preprocesses the data, extracts features from the text, and trains the model.
    - Uses the trained model to classify new news articles as fake or true.

## References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Codebasics Youtube Channel](https://www.youtube.com/channel/UCh9nVJoWXmFb7sLApWGcLPQ)
- [Fake News Dataset](https://www.kaggle.com/datasets/competitions)

## Conclusion

This project demonstrates how to classify news articles as either fake or true using the Naive Bayes algorithm. By training the model on a news dataset, the project can accurately classify new articles based on their content. Customize and extend this project to suit your needs and explore different models and approaches for news classification.
