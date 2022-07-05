# Unsupervised Machine Learning - Songs Clustering

## Introduction
Different playlists are made from a dataset of approximately 5000 songs using the K-means clustering algorithm.

## Description
The following Spotify audio features are used to determined whether a song is similar to each other or not by calculating the Euclidean distance between each data point.

- acousticness
- danceability
- duration_ms
- energy
- instrumentalness
- key
- liveness
- loudness
- mode
- speechiness
- tempo
- time signature
- valence

All audio features are first scaled using either the standard, robust or min max scaler based on the presence or absence of outliers. Then the K-means algorithm is applied to group the songs into different clusters. Inertia and silhouette scores are used to determine the optimal number of clusters. To prevent each playlist from having too many songs, only 20 clusters or more are considered. All titles, artists and several songs from each cluster are picked and listened to in order to evaluate whether the algorithm has done a good job in grouping similar songs.

## Tools
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Scikit-learn
- Word cloud

