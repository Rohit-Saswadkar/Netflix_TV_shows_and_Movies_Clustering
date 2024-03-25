
## Netflix Dataset Analysis and Recommendation System

### Project Overview

The project focuses on analyzing the Netflix Dataset of movies and TV shows until 2019, obtained from the third-party search engine Flixable. The primary objective is to enhance user experience and reduce subscriber churn through a recommendation system. With over 220 million subscribers, this system is crucial for Netflix's success.

### Methodology

1. **Handling Null Values**: Addressed null values in the dataset to ensure data integrity and accuracy.
2. **Managing Nested Columns**: Processed columns with nested data like director, cast, listed_in, and country for better visualization and analysis.
3. **Binning Ratings**: Categorized the rating attribute into groups such as adult, children's, family-friendly, and not rated for analysis and recommendation.
4. **Exploratory Data Analysis (EDA)**: Employed EDA techniques to gain insights, understand patterns, and prevent subscriber churn.
5. **Creating Clusters**: Applied clustering techniques based on attributes like director, cast, country, genre, rating, and description. Tokenized, preprocessed, and vectorized these attributes using the TF-IDF vectorizer.
6. **Dimensionality Reduction**: Reduced the dataset's dimensionality using Principal Component Analysis (PCA) to enhance performance and eliminate noise.
7. **Clustering Algorithms**: Utilized K-Means Clustering and Agglomerative Hierarchical Clustering algorithms to create clusters. Determined the optimal number of clusters (4 for K-Means, 2 for hierarchical clustering) using various evaluation methods.
8. **Content-Based Recommender System**: Developed a content-based recommender system using the cosine similarity matrix to offer personalized recommendations. The goal is to reduce churn by providing relevant and engaging content.

### Conclusion

This project's comprehensive analysis and recommendation system aim to boost user satisfaction and reduce subscriber churn for Netflix. By clustering content and providing personalized recommendations, it's expected to improve user retention rates and solidify Netflix's position as a leading streaming entertainment platform.
