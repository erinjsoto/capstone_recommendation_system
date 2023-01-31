# MIT ADSP Final Capstone Project
## Recommendation System - Spotify Data
### capstone_recommendation_system

Spotify is a digital music platform that provides over 80 million songs, 4 million podcasts, and most recently 300,000 audiobooks to its premium users. The once-originally music-based platform uses big data to supply personalized services such as recommendation systems. These services enhance the overall user experience and (if done right) help keep a loyal user population.

When going about this project it’s important to understand the problem. How do we supply a better musical experience to our users in this use case? For Spotify to see business growth we’ll need to tackle keeping our customers engaged in our product. How do we do this? By offering personalized services such as song recommendations. With song suggestions, we can cut tedious scrolling and shuffling to find the right songs for the users. This offers immediate satisfaction and increases user engagement.

This project aims to work through four different recommender systems to find the best predictive model according to key indicator measurements such as RMSE, Precision, Recall, and F_1 score. Through the code, I work on basic models and then implement 3-fold cross-validation to tune the hyperparameters per the model. The specific models used were **User-to-User**, **Item-to-Item**, Matrix Factorization, and Cluster-based recommendation systems.
