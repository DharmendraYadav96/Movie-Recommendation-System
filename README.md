# Movie-Recommendation-System

## Objective
Build a recommender system which would recommend the 5 most similar movies to a movie query.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Usage](#usage)
- [Future Work](#Future Work)

## Introduction
A recommendation system is a type of algorithm designed to provide personalized suggestions or recommendations to users. These recommendations are typically based on the user's preferences, behavior, and historical interactions with a system or platform.
This is a Content based Movie Recommendation System implemented using the k-Nearest Neighbors algorithm. The system provides movie recommendations based on user preferences and similarities between users' movie-watching histories.

## Dataset
In the given dataset, we are given a lot of information about a particular movie. We need to restrict ourselves to the columns - Movie ID, Movie Name, Popularity and genres.
### Variable description
1. id: contains id for each movie id.
2. name: Contians name of each movie.
3. Popularity: contains the popularity in numerical format.
4. genre: in json format, contain list of dictionary. Each dictionary has a genre.

## Features

- User-based collaborative filtering for movie recommendations.
- Efficient k-Nearest Neighbors algorithm for finding similar users.
- A user-friendly interface for inputting user preferences.
- Recommendations based on  movie similarities.

## Future Work
1. Combining content-based algorithm: We plan to enhance the recommendation system by combining it with other recommendation algorithms, such as collaborative filtering or matrix factorization.
2.  Deployment: We aim to deploy this recommendation system as a web application or API, making it accessible to a wider audience.



