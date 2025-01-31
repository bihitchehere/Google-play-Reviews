# Tiny ReviewAnalyzer 📊🤖

ReviewAnalyzer is a Python-based tool designed to apply **clustering** and **NLP techniques** to sort text data from **negative reviews** in the **Google Play Store** into meaningful categories. By analyzing and clustering the content of negative reviews, we can uncover recurring themes and topics, helping app publishers improve their apps and better address user concerns.

## Project Description 📱💬

App publishers want to understand what users think and feel about their apps. While we can't read their minds, we can **data-mine** the reviews they leave to uncover the main topics!

In this project, we apply clustering and NLP techniques to sort **negative reviews** from the Google Play Store into categories. By analyzing the content of negative reviews, we can identify common issues and improve the user experience.

## Data Description 📊

The dataset used for this project consists of app reviews from the Google Play Store, which includes:

- **score**: The rating given by the user (e.g., from 1 to 5).
- **content**: The text of the review left by the user.
- **date**: The date when the review was posted (optional).
- **app_name**: The name of the app being reviewed (optional).

The focus is on analyzing **negative reviews** (ratings from 1 to 2) to extract meaningful insights about user dissatisfaction.

## Tools Used 🛠️

This project uses several Python libraries and tools to perform text preprocessing, clustering, and visualization:

- **Python 3.x**: The programming language used for the project.
- **pandas**: For data manipulation and processing.
- **numpy**: For numerical operations.
- **scikit-learn**: For implementing K-means clustering and other machine learning techniques.
- **nltk**: For natural language processing tasks such as tokenization and stopword removal.
- **matplotlib & seaborn**: For visualizing the distribution of reviews across clusters.
- **wordcloud**: For generating word clouds to visualize the most frequent words in each cluster.
- **plotly**: For interactive visualizations (optional).

## Features 🛠️

- **Text Preprocessing**: Cleans and tokenizes review content, removing stopwords and non-alphabetic words.
- **K-means Clustering**: Automatically determines the optimal number of clusters based on silhouette scores and clusters reviews accordingly.
- **Cluster Insights**: Provides the top terms for each cluster and sample reviews from each group.
- **Visualizations**: Generates distribution plots and word clouds to visually represent clusters.

## Requirements ⚙️

Make sure to install the following dependencies:

- Python 3.x
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn
- wordcloud


You can install the dependencies using `pip`:


