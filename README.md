# Reddit Headline Sentiment Analysis

This project was a requirement for one of my classes during my Master's Data Science program at Bellevue Univeristy.

#### -- Project Status: `In-Progress`

## Project Intro/Objective
The primary purpose of this project is to conduct natural language processing (NLP), particularly sentiment analysis, on open text.

### Methods Used
* Machine Learning (Sentiment Analysis: Vader, Roberta)
* Data Visualizaiton (Matplotlib, Seaborn)
* Summary Statistics

### Technologies Used
* Python (Pandas, NumPy, nltk)
* DataSpell (Data Science IDE)

## Project Description
The first step in this project was data collection. I leveraged the Python Reddit API Wrapper (PRAW) library to collect data from Reddit's exposed API they have for developers. I chose to collect information from [r/politcs](https://www.reddit.com/r/politics/). After the data was collected, I processed the data so that it could be stored in a Pandas dataframe. The primary Python package that was used for this project what the Natural Language Toolkit (NLTK) which comes packed with so many useful natural language processing capabilities. For this project, I only used the SentimentIntensityAnalyzer() function to genereate sentiment values in the form of polarity scores. These scores were combined into a useful `compound` metric that was used to encode a new label column that had distinct categorical values for `postiive`, `neutral`, and `negative` sentiment flavors. In order to analyze the performance of the trained sentiment analysis model, I used visualizations created using Seaborn and Matplotlib. I also created a WordCloud diagram that depicted the most common words measured in the dataset. For further detail on my project findings as well as the project methodology, please refer to the other files in this repo.
