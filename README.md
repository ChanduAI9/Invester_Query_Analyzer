# Invester_Query_Analyzer


Title: Green Hydrogen Stock Analysis(This was a topic) - Trend Detection and Sentiment Analysis

Description:

This project explores the recent surge in interest around "Green Hydrogen" and identifies potential investment opportunities. It leverages web scraping and natural language processing (NLP) techniques to analyze news articles and extract valuable insights.

Key Components:

Data Collection:
Web scraping headlines from CNBC and Google News RSS feeds containing "green hydrogen" keyword.
Storing data in a pandas DataFrame with news date and source.
Sentiment Analysis:
Utilizing a pre-trained sentiment analysis model from Hugging Face to score each news headline.
Adding a sentiment score column to the DataFrame.
Named Entity Recognition (NER):
Employing a Hugging Face NER model to identify organization names mentioned in the headlines.
Visualization:
Generating a graph depicting the weekly average sentiment score for all news articles.
Creating a word cloud showcasing the most frequent organization names.
Deployment:
Converting the analysis results to a CSV file.
Uploading the CSV file to a Google Sheet with public access using the Google Sheets API in Python.
Benefits:

Provides investors with early insights into potential green hydrogen stocks.
Offers quantitative analysis backed by NLP techniques.
Creates visually appealing presentations of trends and key players.
Technologies Used:

Python
Pandas
NLTK or Hugging Face libraries for sentiment analysis and NER
Google Sheets API
Getting Started:

Clone the repository.
Install required dependencies.
Run the Jupyter Notebook or Python script.
Access the Google Sheet with the analysis results.
