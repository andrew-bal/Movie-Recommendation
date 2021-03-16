# Movie Recommendation Engine


**Introduction**

The enclosed Jupyter Notebook contains a movie recommender system based on data about close to 5000 movies and TV series. The dataset contains information such as budget, cast, crew, genre, etc. The recommendation engine requires a movie as the input, and it will recommend 10 movies that are similar to the chosen movie.


**Problem Statement**

Can we recommend 10 similar movies to the one that a user specifies based on information about the movies?


**Approach**

After some data preparation, I created a content-based recommendation engine that suggests 10 similar movies to the input movie. The function takes into consideration the genre, keywords, director and cast. I combined these features, which serves as the basis for determining movie similarity. 
