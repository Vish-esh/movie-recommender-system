# Movie Recommendation System using Content-Based Filtering

## Overview
This project implements a movie recommendation system based on content-based filtering. 

Content-based filtering recommends items to users based on the features of the items and a profile of the user's preferences. In this system, movies are recommended to users based on the similarity of their features (such as genre, cast, director, etc.) to the movies they have liked in the past.

![content based ](https://github.com/ArchitArora03/Movie-Recommendation-system/assets/97459906/00287a00-fe13-4ba0-a018-5a9047568b6b)

*****************************


## Dataset Information
The dataset used for building the recommendation system is sourced from The Movie Database (TMDB).

Link : https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
******************************



## Approach

The content-based recommendation system follows these steps:

Feature Extraction: Extract relevant features from the movie dataset.

Vectorization: Convert the textual features (like plot summary) into numerical vectors.

Similarity Calculation: To decide which item is most similar to the item user likes we use the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

Cosine similarity: It is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
![cosine similarity](https://github.com/ArchitArora03/Movie-Recommendation-system/assets/97459906/582645d4-2dff-4d5e-bd4d-569b402cb2e3)

******************************

## Demo


https://github.com/ArchitArora03/Movie-Recommendation-system/assets/97459906/9c75c70f-c753-4935-8bd5-5fa6ba7a974e

******************************
## Contributing
Contributions to this project are welcome. If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.


