Netflix_Movies_-_TV_Show_Clustering_Unsupervised_ML
Netflix Dataset Analysis and Recommendation System
This project aims to analyze the Netflix Dataset of movies and TV shows until 2019, obtained from the third-party search engine Flixable. The primary objective is to group the content into relevant clusters using NLP techniques to enhance the user experience through a recommendation system. This system will help mitigate subscriber churn for Netflix, which currently boasts over 220 million subscribers.

Moreover, this project seeks to uncover valuable insights and trends in the streaming entertainment industry by analyzing the dataset.

Project Overview The project was carried out in the following step-by-step process:

Handling Null Values: Null values in the dataset were addressed to ensure data integrity and accuracy.

Managing Nested Columns: Columns containing nested data, such as director, cast, listed_in, and country, were processed to enable better visualization and analysis.

Binning Ratings: The rating attribute was binned into categories such as adult, children's, family-friendly, and not rated to facilitate analysis and recommendation.

Exploratory Data Analysis (EDA): EDA techniques were employed to gain insights and understand patterns and trends in the dataset, with the goal of preventing subscriber churn.

Creating Clusters: Clustering techniques were applied to group the content based on attributes like director, cast, country, genre, rating, and description. These attributes were tokenized, preprocessed, and vectorized using the TF-IDF vectorizer.

Dimensionality Reduction: The dimensionality of the dataset was reduced using Principal Component Analysis (PCA) to improve performance and eliminate noise.

Clustering Algorithms: Both K-Means Clustering and Agglomerative Hierarchical Clustering algorithms were utilized to create clusters. The optimal number of clusters was determined (4 for K-Means and 2 for hierarchical clustering) using various evaluation methods.

Content-Based Recommender System: A content-based recommender system was developed using the cosine similarity matrix to provide personalized recommendations to users. The aim was to reduce subscriber churn by offering relevant and engaging content.

The comprehensive analysis and recommendation system developed in this project are expected to enhance user satisfaction and ultimately improve subscriber retention rates for Netflix.

Conclusion
By conducting this comprehensive analysis of the Netflix dataset and developing a content-based recommendation system, the project aims to enhance user satisfaction and reduce subscriber churn for Netflix. The clustering of content allows for improved grouping and organization, while the recommender system provides personalized recommendations based on user preferences. It is expected that these efforts will lead to higher user retention rates and ultimately benefit Netflix in maintaining its position as a leading streaming entertainment platform.
