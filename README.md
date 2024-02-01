# Netflix Movies TV shows Clustering
# OBJECTIVE
The project involved analyzing a dataset of TV shows and movies available on Netflix as of 2019. The dataset, collected from Flixable, contained about 7787 records and 11 attributes. The goal was to classify the shows into clusters based on their similarity using text clustering techniques.
The project began with dealing with missing values and conducting exploratory data analysis (EDA). Clusters were created using attributes such as director, cast, country, genre, rating, and description. The values in these attributes were tokenized, preprocessed, and then vectorized using TFIDF vectorizer. Principal Component Analysis (PCA) was used to handle the curse of dimensionality.
Two types of clusters were built using the K-Means Clustering and Agglomerative Hierarchical clustering algorithms. The optimal number of clusters was determined using techniques such as the elbow method, silhouette score, and dendrogram. Additionally, a content-based recommender system was built using the similarity matrix obtained after using cosine similarity. This recommender system provided 10 recommendations to the user based on the type of show they watched.
The project utilized natural language processing (NLP) and unsupervised machine learning techniques to analyze the dataset, including K-Means, Hierarchical clustering, and PCA. The analysis aimed to provide valuable insights into the content available on Netflix and to create a recommendation system based on the similarity of shows.

# Problem Statement
Netflix is the world's largest online streaming service provider, with over 220 million subscribers as of 2022-Q2. It is crucial that they effectively cluster the shows that are hosted on their platform in order to enhance the user experience, thereby preventing subscriber churn.
We will be able to understand the shows that are similar to and different from one another by creating clusters, which may be leveraged to offer the consumers personalized show suggestions depending on their preferences.
The goal of this project is to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

# Attribute Information

show_id : Unique ID for every Movie / Tv Show
type : Identifier - A Movie or TV Show
title : Title of the Movie / Tv Show
director : Director of the Movie
cast : Actors involved in the movie / show
country : Country where the movie / show was produced
date_added : Date it was added on Netflix
release_year : Actual Releaseyear of the movie / show
rating : TV Rating of the movie / show
duration : Total Duration - in minutes or number of seasons
listed_in : Genre
description: The Summary description




# CONCLUSION
The project aimed to analyze a dataset of TV shows and movies available on Netflix as of 2019. The dataset contained about 7787 records and 11 attributes. The goal was to classify the shows into clusters based on their similarity using text clustering techniques.
The project began with dealing with missing values and conducting exploratory data analysis (EDA). Clusters were created using attributes such as director, cast, country, genre, rating, and description. The values in these attributes were tokenized, preprocessed, and then vectorized using a TFIDF vectorizer. Principal Component Analysis (PCA) was used to handle the curse of dimensionality.
Two types of clusters were built using the K-Means Clustering and Agglomerative Hierarchical clustering algorithms. The optimal number of clusters was determined using techniques such as the elbow method, silhouette score, and dendrogram. Additionally, a content-based recommender system was built using the similarity matrix obtained after using cosine similarity. This recommender system provided 10 recommendations to the user based on the type of show they watched.
The project utilized natural language processing (NLP) and unsupervised machine learning techniques to analyze the dataset, including K-Means, Hierarchical clustering, and PCA. The analysis aimed to provide valuable insights into the content available on Netflix and to create a recommendation system based on the similarity of shows.
