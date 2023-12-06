# Movie Recommendation System
![image](https://github.com/AmiraQadry/Movie-Recommendation-System/assets/106974489/f14d4dac-6894-4289-b7b9-c0a702e45fa7)

## Overview

This project implements a movie recommendation system using collaborative filtering, is a type of recommendation system that relies on the past behavior of similar users/items to make recommendations, with the KNNBasic algorithm. KNN stands for k-nearest neighbors, and this algorithm makes recommendations by finding a set of similar items or users in close proximity and predicting ratings based on them, from the Surprise library in Python. 
The system suggests movie recommendations based on user preferences and browsing history.

## Requirements

- Python
- [Surprise library](http://surpriselib.com/): Install with `pip install scikit-surprise`

## Dataset

The project utilizes the [MovieLens dataset](https://www.kaggle.com/datasets/parasharmanas/movie-recommendation-system/data), a widely used dataset in the field of recommender systems, 
containing movie ratings and metadata. 
The dataset is preprocessed to create a user-item matrix and to calculate item similarity using cosine similarity. 
This enables the system to identify movies that are similar to the ones the user has previously enjoyed and recommend them accordingly.
The data is loaded using Surprise library which provides Sample datasets as follows:

- ml-100k: MovieLens dataset containing 100,000 ratings.
- ml-1m: MovieLens dataset containing 1,000,000 ratings.
- jester: Jester dataset. Anything that includes online joke ratings.
- bookcrossing: Book-Crossing dataset. Including book ratings.
- movielens: MovieLens dataset. There are four versions, 100k, 1M, 10M and 20M, each containing a corresponding number of ratings.



