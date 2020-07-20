# AmazonRecommendationSystem

AMAZON RECOMMENDATION SYSTEM:

ABSTRACT:
E-commerce companies like Amazon uses different recommendation systems to provide suggestions to the customers. Amazon uses currently item-item collaberrative filtering, which scales to massive datasets and produces high quality recommendation system in the real time. This system is a kind of a information filtering system which seeks to predict the "rating" or preferences which user is interested in. This project aims to build a recommendation system for Amazon based on the previous ratings of the customer. Dataset is downloaded from kaggle.com.

WHAT HAVE I DONE?
I have first loaded the dataset and then handled the missing values, checked distribution of ratings and then found no. of unique users, products and ratings. Ratings are then analyzed and a recommender system is built.

HOW HAVE I DONE?
The algorithm that has been used here is Model based collaborative filtering.  The goal is to train models to be able to make predictions. For example, we could use existing user-item interactions to train a model to predict the top-5 items that a user might like the most. One advantage of these methods is that they are able to recommend a larger number of items to a larger number of users, compared to other methods like memory based approach. They have large coverage, even when working with large sparse matrices.

CONCLUSION:
The project is successful in recommending top 25 highly correlated products in sequence (or any number of products we wish to recommend).
