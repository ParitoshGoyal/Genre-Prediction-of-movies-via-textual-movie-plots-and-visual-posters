# Genre-Prediction-of-movies-via-textual-movie-plots-and-visual-posters
This repository contains one of my projects in Deep Learning and Machine learning.
The project is based on problem of multi label classfication and it's target is to predict genres of a given movie under supervised conditions, where there are two types of input features - (i)textual plots of movie and (ii)poster of movie.
The first notebook contains code(along with description) of how data for movies with their posters is collected from tmdb website using tmdbsimple api. Next three notebooks contain different models for predicting genre. In each model, for performance evaluation, I have used Precision-Recall metric.

In the project, different python notebooks go as follows:
1. Data Crawler-Scrapper and Dataset builder
2. Non-Deep Conventional Machine Learning Models with movie plots(textual data), Models used: SVM and Naive Bayes
3. Deep Learning using Convolutional Neural Networks for predicting Genre from poster of movies
4. Deep Learning for genre prediction using textual features, Model used: word2vec

Conclusion of the analysis: The Deep learning based model on textual plot of movie gives an accuracy of upto 85% for multi lable classification problem. Non-deep Conventional machine learning models on textual plot are less accurate (with precision value=0.48893866021 and recall value=0.521633554084). In addition to that, CNN based model on Poster images is lesser accurate(with precision value=0.492592592593 and recall value=0.491543209877) because of a small dataset(1300 images only) and constrained computational powers (personal computer of 4GB RAM).

Important note: I have used camelCase for all variable names and '_' for connecting to words in names of function, for eg: get_poster

People who go through my project, please help me improve upon this by providing your valuable feedback.
