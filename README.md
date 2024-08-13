# Movie Recommendation System

A simple movie recommendation system built using Python and pandas, leveraging TF-IDF vectorization and cosine similarity to recommend movies based on a user's input.

## Features

- **Data Loading**: Reads movie data from a CSV file.
- **Data Preprocessing**: Handles missing data using `fillna`.
- **Vectorization**: Uses `TfidfVectorizer` to convert text data into feature vectors.
- **Similarity Calculation**: Computes cosine similarity between movies to generate a similarity score vector.
- **Recommendation**: Recommends a list of movies based on a given movie name.
