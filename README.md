# Movies_recommendation_system

Overview
This is a machine learning-based movie recommender system designed to provide personalized movie suggestions based on movie attributes and content. It was built using a dataset of over 4,800 movies, ensuring both highly diverse and accurate recommendations.

Key Features
Movie Recommendations: Curates personalized movie suggestions based on user preferences and input.
Machine Learning: Implements advanced techniques such as Cosine Similarity and TF-IDF Vectorization for enhanced recommendation accuracy and contextual relevance.
Libraries Used:
Pandas for data manipulation and analysis.
Scikit-learn for machine learning model building and evaluation.
Difflib for efficient string matching and movie comparison.
Dataset
The model is trained on a dataset of over 4,800 movies, sourced from IMDB, which includes movie attributes such as genre, director, actors, and plot keywords.

How It Works
The system uses Cosine Similarity to measure the similarity between movies based on their attributes.
TF-IDF Vectorization transforms the textual data into numerical representations, allowing the model to better understand the relevance of each word in a movie's description.
The system then recommends movies by matching user input with similar movies in the dataset.
