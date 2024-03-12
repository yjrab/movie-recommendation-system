# movie-recommendation-system

This project aims at creating a recommendation system for movies.\
The system utilises the concept of embeddings to detect and recommend movies simlar to the movies liked by the user. The system learns user embeddings and movie embeddings through matrix factorization. Movies recommended would then be either movies similar to movies the user likes or movies liked by another user that is similar to the user. A user being similar to another user is translated by having similar user embeddings.

The system includes the feature of asking the user about ratings for some movies. Doing so allows the system to understand what movies the user likes and recommend similar movies.
