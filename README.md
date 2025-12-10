# ITAI2373-NewsBot-MidtermNewsBot Intelligence System
Project Overview

NewsBot is an NLP-powered news classification system that automatically classifies news articles into predefined categories. This project uses machine learning and natural language processing techniques to demonstrate how different algorithms and models can be applied to real-world user-friendly simple classifications.
---
# Objective
The goal of this project is to create a fully functional NLP system that:

- Classifies news articles into one of several predefined categories (e.g., Politics, Technology, Sports, Entertainment).
- In the future will exact much more complexity with sentiment analysis
--- 
# Why this is valuable:

News classification and future sentiment analysis help media organizations automate content categorization, improve recommendation engines, and enhance user experience. 
---
## Key Features

News Classification: Classifies articles into categories like Sports, Business, Technology, Politics, etc.
---

## Data

The dataset used for this project is the News Category Dataset from Kaggle, which contains news articles in English across multiple categories. The dataset contains a minimum of 500 articles and includes:

- Article text content

- Category labels (for classification)

- Clear, labeled text content for NLP tasks

You can access the dataset here:
## https://www.kaggle.com/datasets/gpreda/bbc-news
#
- Dataset Details: Self updating dataset. It collects RSS Feeds from BBC News using a Kernel: https://www.kaggle.com/gpreda/bbc-news-rss-feeds. The Kernel is run with a fixed frequency and the dataset is updated using the output of the Notebook.

- Number of Articles: 500+ (ensure the dataset meets the requirements)

- Categories: At least 4 (e.g., Politics, Technology, Sports, Entertainment)

- Language: English

- File Format: CSV

# Installation and Setup

Follow the steps below to get the project running locally or on Google Colab:

Clone the repository:

git clone https://github.com/mrivassnj-svg/ITAI2373-NewsBot-Midterm.git
cd your-repository-name


Install the required dependencies. If you're running the code locally, make sure you have the necessary Python libraries:

pip install -r requirements.txt


If using Google Colab, open the ITAI2373-NewsBot-Midterm(Final).ipynb notebook, and follow the instructions within the notebook to load and process the dataset.

How to Run

Open the ITAI2373-NewsBot-Midterm(Final).ipynb notebook in Google Colab.

Ensure you have the dataset uploaded to your Colab session.

Run the notebook sequentially to:

- Load the dataset.

- Preprocess the text.

- Train the classification model.

- Evaluate the model's performance.

- Modules and Code Structure

This repository contains the following main components:

- Data Loading & Preprocessing: Code for loading the dataset and cleaning/preprocessing the text data (removing stopwords, stemming, lemmatization, etc.).

- Model Training: Code for training machine learning models (e.g., Naive Bayes, SVM) for news classification.

- Evaluation: Evaluation scripts to assess the accuracy, precision, recall, F1-score, and confusion matrix for model performance.

# Requirements

- Python 3.x

- Pandas

- Scikit-learn

- Matplotlib/Seaborn (for visualization)

- Jupyter Notebook (if running locally)

#### For Google Colab, these libraries will be installed automatically.
