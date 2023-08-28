# Image Similarity Retrieval System

This repository contains code for an Image Similarity Retrieval System. The system utilizes a pre-trained VGG16 model for feature extraction and cosine similarity for calculating similarity metrics between images.

## Contents

- `similarity_prob.py`: This script calculates the similarity between two images using the VGG16 model for feature extraction and cosine similarity for similarity metrics.
- `database_building.py`: This script saves directory names, image names, and their corresponding feature vectors in a database. These features can later be used for comparing similarity between images.
- `querying_similar_image.py`: This script queries the database to retrieve a list of similar images for a given input image.

