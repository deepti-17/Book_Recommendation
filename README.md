Book Recommendation System


This project is a Book Recommendation System that uses a collaborative filtering approach to recommend books based on user ratings. It leverages a dataset of over 47,000 ratings and 2,400 books to generate personalized book suggestions for users. The system implements the K-Nearest Neighbors (KNN) algorithm to recommend books similar to those that the user has rated highly.

Features

Collaborative Filtering: Recommends books based on the ratings given by users, using the KNN algorithm to find the most similar items.

Data Preprocessing: Handles missing data, duplicates, and performs data normalization before building the recommendation model.

Model Implementation: Utilizes the KNN algorithm to identify the nearest neighbors of a book based on user ratings.

Recommendation Generation: Provides personalized book recommendations based on the user's rating history and preferences.

Tech Stack

Programming Language: Python

Libraries: pandas, numpy, scikit-learn (for KNN), matplotlib (for visualizations)

Data: Dataset of 2,400+ books and 47,000+ user ratings (can be found in the books.csv and ratings.csv files)
