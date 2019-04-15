# Movie Recommender System
This is a machine learning project in python, aimed at creating a basic recommendation system for movies

We use *model-based collaborative filtering* to figure out the moive recommendations from the data set.
Data set: https://grouplens.org/datasets/movielens/100k/

We use the user data (u.data) and Movie data (u.item), with common key on movie id (item_id).

We create two types of systems:
  1) Greater than 90% correlations (somewhat generic)
  2) Greater than 95% correlations (even more personalised)

**Model used for training the data:** TruncatedSVD from sklearn.decompose

**Dependencies:**
  numpy
  pandas
  sklearn
  sklearn.decomposition.TruncatedSVD

**Files:** MovieRecSys.ipynb
**Data folder:** ml-100k
