Overview
This project analyzes your web browsing history to identify the dominant topics based on the titles of visited pages. Using Natural Language Processing (NLP) techniques and Latent Dirichlet Allocation (LDA), the analysis classifies URLs into topics and visualizes trends over time.

Requirements
Python 3.x
pandas
numpy
requests
BeautifulSoup4
nltk
gensim
wordcloud
matplotlib
Installation
bash
Copy code
pip install pandas numpy requests beautifulsoup4 nltk gensim wordcloud matplotlib
Usage
Prepare Data: Export your browser history as history_export.txt with each line containing a timestamp and a URL, separated by a pipe (|).
Run Analysis: The script processes the history file, extracts page titles, tokenizes text, removes stop words, and applies stemming.
Topic Modeling: Using LDA, the script generates a set of topics and visualizes their distribution over time.
Visualization: The script produces various plots, including topic distributions over the days of the week.
Output
chrome_history.csv: Contains the processed history with topics assigned.
Visualization plots showing topic trends over time.
