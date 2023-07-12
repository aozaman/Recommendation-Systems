# Recommendation-Systems
This project focuses on implementing recommendation systems for online streaming platforms. Two approaches are explored: a rank-based recommendation system and a collaborative filtering-based recommendation system.

STEPS INVOLVED

Rank-Based Recommendation System:

- Calculate the average rating for each movie.
- Rank the movies based on their average ratings.
- Create a summary data frame with movie ID, average rating, and rating count.
- Identify the top 10 movies with at least 100 interactions.

Collaborative Filtering-Based Recommendation System:

- Clean the data, handling missing values as needed.
- Predict movie ratings using the KNNRegressor model.
- Split the data into training and test sets.
- Train the KNNRegressor model on the training data.
- Evaluate the model's performance using Root Mean Squared Error (RMSE).
- Predict the rating for a specific user (ID 4) and movie (ID 10).

CONCLUSION

The rank-based system ranks movies based on average ratings, while the collaborative filtering-based system uses user-item interactions to make personalized recommendations. By improving the recommendation process, customer satisfaction and retention can be enhanced.
