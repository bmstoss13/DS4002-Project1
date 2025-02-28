# DS4002 Project 1 - Spam vs. Ham Email Detection

The goal of our project is to build a model that identifies spam emails with at least 95% accuracy. We first cleaned and preprocessed the textual email data, then used three algorithms (K-Nearest Neighbors, Logistic Regression, and Decision Trees) to identify emails as spam or not spam. We then analyzed model performance based on precision and accuracy levels to determine the highest performing algorithm in detecting spam emails. 

## Software/Platform

In our project, we used Jupyter notebook to run our Python code on a Mac computer. To run the code, the following packages must be installed: 
- pandas as pd
- numpy as np
- matplotlib.pyplot as plt
- seaborn as sns
- from wordcloud import WordCloud
- from collections import Counter
- re
- nltk
- nltk.download('stopwords')
- nltk.download('punkt')
- string
- from nltk.corpus import stopwords
- from nltk.stem import PorterStemmer
- from nltk.tokenize import sent_tokenize, word_tokenize


## Map of Documentation
![Project 1 Hierarchy](https://github.com/user-attachments/assets/b5651aaf-c7bd-4d94-a71e-6671611a6a78)

## Reproducing Results

1. Ensure that you have the necessary Python packages installed/imported into Jupyter Notebook. 
2. Copy DS4002-Project1 folder onto your computer, check that folder structure matches the above map of documentation.
3. From the DATA folder, download the emails.csv dataset.
4. In the SCRIPTS folder, execute ProcessingScript_EDA.ipynb. This script performs necessary data cleaning and text preprocessing using emails.csv, as well as illustrates important relationships between variables through graphs and tables. Finally, this file outputs a cleaned dataset -- preprocessed_data.csv -- that will be used in AnalysisScript.ipynb. 
5. Execute AnalysisScript.ipynb. This file uses preprocessed_data.csv to run the three models: KNN, Logistic Regression, and Decision Tree. Once the models are built, they are compared based on precision and accuracy levels. The file will identify the highest performing model, as well as compare the precision and accuracy levels of each model. 
