# Movie Recommendation System

This repository features a collaborative filtering movie recommendation system developed with TensorFlow. Trained on user ratings from ratings_small.csv, the model employs embeddings for users and movies, yielding personalized movie suggestions. Key components include:

Model Training: Utilize the Jupyter Notebook (MovieRecommender.ipynb) for data preprocessing, model training, and recommendation generation, optimizing the model on the provided dataset.

Datasets: Ensure the availability of necessary datasets (movies_metadata.csv and ratings_small.csv) for model training.

Embedding Vectors: Extracted movie embedding vectors are stored in vecs.tsv, accompanied by meta.tsv containing corresponding movie titles.

Deployment Goal: The ultimate aim is deploying the model using JavaScript, facilitating seamless interaction for users.

Model Architecture: The architecture features separate embedding layers for movies and users, establishing a robust foundation for learning.
