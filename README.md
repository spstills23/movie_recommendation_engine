# movie_recommendation_engine
movie recommendation generator 

* imported a movie dataset csv file and used sklearn and machine learning algorithms to recommend movies based off your inputed favorite.
* Engineered features to use in the algorithm: "overview", "keywords", "cast", "genres", "director".
* Combined the features into one string and used CountVectorize to convert the collection of text to token counts
* Used the Cosine Similarity to create a matrix showing the similar movies based off the features combined
* Created a function to be able to look through then index of movies to return a movie title that matches the similarity index.
* Returns the top 'n' movies based off your inputed 'favorite movie'.
