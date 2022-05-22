# Movie-Recommender-System
Using TMDB database for movie created a content based recommender system.
The data used in this project can be found in-
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

This project will recommend similar movies with respect to the movie one enters.
It does so by finding cosine similaritites between embedding vectors of the dataset of movies.

I created tags of all movies by doing EDA and created an embedding vectors of all the tags and then found cosine similarities of each of them to recommend
the closest movies of the input.

Techniques used in it are-
TFIDF, stemming, EDA

Libraries used are-
nltk, pandas, numpy, etc.
