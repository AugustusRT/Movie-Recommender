# Movie-Recommender

In this project, I create a simple movie scoring algorithm that predicts a users movie ratings based on that user's existing movie ratings and the ratings of similar users. The data is from the MovieLens database (details in the Data section).

The idea here is that we have a table of movies and many viewers, and each viewer as watch some tiny fraction of the movies and rated them. The output of this algorithm is the completed table, where the missing ratings for each movie are calculated from group data (similar users). 

I use proximal gradient descent as the optimization algorithm for the penalized problem. 
