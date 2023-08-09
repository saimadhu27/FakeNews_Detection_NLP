# Fake News Detection Using Natural Language Processing

## Overview
This project demonstrates the application of a machine learning model to detect fake news articles. Leveraging natural language processing and classification techniques, the model can assess the credibility of news articles, aiding businesses and users in making informed decisions.

In the age of information, distinguishing between real and fake news is crucial for businesses, individuals, and society. The proliferation of fake news can lead to misinformation, reputational damage, and financial losses. This project addresses the challenge of automating fake news detection to improve decision-making.

Dataset columns:
1. title - The title of the article
2. text - The text of the article
3. subject - The subject of the article
4. date - The date at which the article was posted
5. category - 0: indicating its a fake news, 1: indicating it's a geniuine news.
## Approach:
* When we plot our y variable which is category, the count of both the categories are almost equal, indicating that it is a balanced dataset.
* Combined the title into text column, to perform all the preprocessing steps on this.
* Performed preprocessing steps like tokenisation, stopwords, lemmatization using the NLTK library.
* I have used trigram CountVectorizer and then trained a Multinomial Naive Bayes algorithm on the data.
* Using this machine learning model I have achieved an accuracy of 97%.
