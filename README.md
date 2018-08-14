# Recommender_System_MovieLens
Creating recommender system for Movie Lens data using sklearn pyhton package

MovieLens data has been collected by the GroupLens Research Project at the University of Minnesota. This dataset consists of:

* 100,000 ratings (1-5) from 943 users on 1682 movies
* Demographic information of the users (age, gender, occupation, etc.)

File u.user contains user information, file u.data contains corresponding ratings for the movies given by a user and u.item contains information about the movie. You can check the column names from README file in the dataset folder.

We have 100k ratings for 943 users and 1682 movie combinations. There are 24 columns in u.item out of which last 19 columns are binary specifying the genre of a particular movie (1 denotes belonging and 0 otherwise).

The dataset has already been divided into train (we will use file named ua.base) and test (ua.test) by GroupLens where the test data has 10 ratings for each user, i.e. 9,430 rows in total.

Recommendation system was built using Collaborative filter model for both user-user similarity and item-item similarity based on cosine similarity.
