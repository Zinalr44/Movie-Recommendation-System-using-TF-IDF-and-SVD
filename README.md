# Movie-Recommendation-System-using-TF-IDF-and-SVD
This repository contains a movie recommendation system using TF-IDF and Singular Value Decomposition (SVD). The system recommends movies based on genre similarity.

Key Features:
Genre-based Recommendations: Suggests similar movies by genre.
Efficient Processing: Uses Truncated SVD for dimensionality reduction.
Fast Results: Operates on a sampled similarity matrix.
Usage:
Load Data: movies.csv with movie titles and genres.
TF-IDF Vectorization: Transform genres into a TF-IDF matrix.
Dimensionality Reduction: Apply Truncated SVD.
Compute Similarities: Load or compute the cosine similarity matrix.
Get Recommendations: Use get_recommendations function.
Requirements:
Python 3.x
pandas
numpy
scikit-learn
Files:
movies.csv: Dataset with movie titles and genres.
cosine_sim_svd.npy: Precomputed similarity matrix.
subset_cosine_sim_svd.npy: Sampled similarity matrix for quick recommendations.
