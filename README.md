# Project 1 for DS4002

The goal of our project is to build a model that identifies spam emails with at least 95% accuracy. We first clean and preprocess the textual data, then use three algorithms (K-Nearest Neighbors, Logistic Regression, and Decision Trees) to identify emails as spam or not spam. We then analyze model performance based on precision and accuracy levels to determine the highest performing algorithm in detecting spam email. 

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
![Project 1 Hierarchy (1)](https://github.com/user-attachments/assets/3dec4be1-04ad-4468-9cb2-a2d786d8ac13)


## Reproducing Results

1. Hardware/software requirements for running this project?
2. Copy DS4002-Project1 folder onto your computer, check that folder structure matches the map of documentation.
3. Download the emails.csv dataset.
4. In the SCRIPTS folder, execute the EDA script. This script performs necessary data cleaning and text preprocessing using emails.csv, as well as illustrates important relationships between variables through graphs and tables. 
5. 
