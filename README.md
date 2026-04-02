# Movie-Recommendation-System
This project is a content-based movie recommendation system that suggests similar movies based on user preferences. It leverages Natural Language Processing (NLP) techniques to analyze movie metadata such as cast, crew, and genres, and provides personalized recommendations.

Features :
Recommends movies similar to a selected movie
Uses TF-IDF vectorization for text feature extraction
Applies Cosine Similarity to measure similarity between movies
Handles text preprocessing for better accuracy
Simple and efficient recommendation pipeline

Tech Stack :
Python
Pandas, NumPy
Scikit-learn (TF-IDF, Cosine Similarity)

Dataset :
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

How It Works :
Data preprocessing (handling missing values, combining text features)
Text vectorization using TF-IDF
Similarity calculation using Cosine Similarity
Recommend top N similar movies based on similarity scores

Example :
Input: Avatar
Output: List of similar movies based on content features

Conclusion :
This project demonstrates how NLP techniques can be used to build real-world recommendation systems, improving user experience by delivering relevant and personalized suggestions.
