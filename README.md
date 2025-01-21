# Movie-recommendation-System
This project utilizes pandas, Scikit-learn, numpy, pickle, streamlit(creating simple and elegant web applications in pure Python) to create a basic project on movie recommendation system. The system is designed to take an input of movies from the user and recommend five similar movies from the tmdb-5000-movies available on kaggle [(https://www.kaggle.com/datasets/tanvirshera/tmdb-5000-movies)]

Features
Recommends five movies similar to the input movie from the tmdb_5000_movies Dataset.
Utilizes Scikit-learn for calculating nearest neighbors for recommendation.
Target Audience
This project is beneficial for developers and machine learning enthusiasts looking to understand and implement movie recommendation systems.

Technical Details
Python 3.9.0 is used for development.
TensorFlow 2.10, Scikit-learn 1.3.0, Numpy, Pickle, tqdm and the ResNet-50 model from TensorFlow are the primary dependencies.
Two pickle files trained on the Fashion Product Images Dataset are required for the system to recommend similar images.
CUDA installation might be required so that Tensorflow can use the dedicated GPU (CUDA can speed up the process of pickle file generation)
