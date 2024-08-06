# Movie-Recommender-System-Project
Git Repository for a movie recommender system project. It is a content based movie recommender system using cosine similarity.

Welcome to the Movie Recommender System project! This project implements a content-based movie recommender system using the TMDB dataset and cosine similarity. The primary goal is to suggest movies to users based on their preferences by analyzing the content of movies they have liked.

# Project Overview
In today's digital age, the abundance of movies available across various platforms can make it challenging for users to decide what to watch next. This recommender system aims to alleviate this problem by providing personalized movie recommendations based on the content of movies the user has previously enjoyed.

# Key Features

Content-Based Filtering: The recommender system uses content-based filtering to analyze various attributes of movies, such as genres, keywords, cast, and crew, to find similarities between movies.

Cosine Similarity: The project leverages cosine similarity to measure the similarity between movie vectors, enabling it to recommend movies that are most similar to the user's preferences.

TMDB Dataset: The system is built using the TMDB (The Movie Database) dataset, which provides extensive information about a wide range of movies, including metadata such as genres, keywords, and more.

Interactive Interface: An easy-to-use interface for users to get movie recommendations based on their selected preferences.
How It Works

Data Preprocessing: The dataset is cleaned and preprocessed to extract relevant features that will be used for similarity calculations.
Vectorization: Movies are represented as vectors in a high-dimensional space, where each dimension corresponds to a feature extracted from the movie's content.

Similarity Calculation: Cosine similarity is computed between the vector of the movie the user likes and all other movie vectors in the dataset.

Recommendation: Based on the similarity scores, the top N movies that are most similar to the user's preferred movie are recommended.
