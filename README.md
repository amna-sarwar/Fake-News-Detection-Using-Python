# Fake News Detection using Machine Learning

## Overview
This project focuses on using machine learning techniques to build an efficient model for detecting fake news articles. With the rise of digital platforms and the rampant spread of misinformation, detecting fake news is becoming more important than ever. This project leverages a variety of machine learning algorithms to classify news articles as either genuine or fake.

## Dataset
The dataset used for this project was sourced from **[Kaggle Fake and Real News Dataset](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)**. It contains the following features:
- **title**: The title of the news article.
- **text**: The main body of the news article.
- **subject**: The category or topic of the news.
- **date**: The date of the article's publication.

The dataset consists of:
- **21,417 true news articles**
- **23,481 fake news articles**

## Project Structure
- **Data Preprocessing**: Cleaning the text data by removing unnecessary elements (punctuations, stop words, etc.) and transforming the text into numerical form using tokenization.
- **Data Exploration**: Visualizing the distribution of true and fake news articles, exploring subjects, and analyzing data balance.
- **Model Building**: Implementing various machine learning algorithms including:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest

- **Model Evaluation**: The models were evaluated based on accuracy, precision, recall, F1-score, and confusion matrix.

## Algorithms and Accuracy
- **Random Forest**: 99.69% accuracy
- **Decision Tree**: 99.61% accuracy
- **SVM**: 99.45% accuracy
- **Logistic Regression**: 98.79% accuracy
- **Naive Bayes**: 93.94% accuracy

## Key Findings
- **Random Forest** performed the best overall, achieving 99.69% accuracy.
- Ensemble methods like **Random Forest** and **Decision Tree** were more effective in detecting fake news compared to individual classifiers.
- Text preprocessing, including stop word removal and tokenization, played a crucial role in improving the model's performance.

## How to Run
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Libraries: Install using the following command:
   ```bash
   pip install -r requirements.txt


# Steps to Execute
# Clone the repository:

git clone https://github.com/amna-sarwar/Fake-News-Detection-Using-Python.git
# Navigate to the project directory:

cd fake-news-detection
# Open the Jupyter Notebook and run the project:

jupyter notebook Fake_News_Detection.ipynb
# Future Work
- Improve the feature extraction by considering bigrams and trigrams.
- Explore deep learning models such as LSTM and GRU for text classification.
- Implement real-time fake news detection based on live streams of news data.
# Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and make your changes in a new branch. Once you're done, submit a pull request.
