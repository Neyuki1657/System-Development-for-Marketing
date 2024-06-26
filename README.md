# System-Development-for-Marketing
For the System Development for Marketing course assignment

In this project, we tried to reproduce popular recommendation algorithms like SVD and ItemKNN on different data sets without using most of the existing popular python recommendation system libraries
This project is centered around the development and evaluation of recommender systems, with a focus on leveraging Singular Value Decomposition (SVD) and Collaborative Filtering (CF) based on Item KNN (K-Nearest Neighbors), along with their respective extensions. Utilizing datasets from Yelp and Movielens, two widely recognized sources in the field of recommender systems, we aim to provide personalized recommendations by analyzing user-item interactions and preferences.

The core of our methodology involves a series of systematic steps starting with exploratory data analysis and data cleaning to ensure the quality and reliability of the datasets.  We conduct exploratory data analysis (EDA) to uncover underlying patterns, relationships, and insights from the data. EDA will help us understand the distribution of users and items, the density of the user-item interaction matrix, and other key characteristics that influence the design of our recommender systems.

Then we proceed to train our models. The SVD and CF ItemKNN algorithms, along with their variations, are employed to predict user preferences and recommend items accordingly. These algorithms are selected for their proven effectiveness in capturing the latent factors and neighborhood relationships inherent in user-item interactions.

Finally, the performance of our models is rigorously tested and compared using appropriate metrics such as RMSE (Root Mean Square Error), MAE (Mean Absolute Error） and NDCG@K （Normalized Discounted Cumulative Gain） score. Through these comparative analyses, we aim to identify the strengths and limitations of each algorithm.
