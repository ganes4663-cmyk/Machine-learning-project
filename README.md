# Machine-learning-project
Movie Recommendation Engine

1. Project Description

The Movie Recommendation Engine is a Python-based project that recommends movies to users based on their previously watched and rated movies.

This project uses the MovieLens Dataset and the K-Nearest Neighbour (KNN) Algorithm to identify similar users and recommend movies.

2. Objectives

- To develop a movie recommendation system.
- To identify users with similar movie preferences.
- To predict movie ratings.
- To recommend movies that users have not watched.

3. Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Jupyter Notebook
- MovieLens Dataset

4. Dataset Description

The MovieLens dataset contains:

- 100,004 ratings
- 9,125 movies
- 671 users
- Each selected user has rated at least 20 movies.

5. Algorithm Used

K-Nearest Neighbour (KNN)

KNN is used to find users with similar movie preferences. Their ratings are used to predict ratings for movies that the current user has not watched.

6. Project Workflow

1. Import required Python libraries.
2. Load movie and rating datasets.
3. Merge movie and rating information.
4. Create a user-movie rating matrix.
5. Calculate similarity between users.
6. Find the nearest neighbours.
7. Predict ratings for unrated movies.
8. Display the top movie recommendations.

7. Output

For User ID 140:

Favourite Movies:

- The Shawshank Redemption (1994)
- Father of the Bride Part II (1995)
- Cast Away (2000)
- The Parent Trap (1998)
- Ocean's Eleven (2001)

Recommended Movies:

- The Godfather (1972)
- Star Wars: Episode V – The Empire Strikes Back (1980)
- The Godfather: Part II (1974)

8. Advantages

- Provides personalized movie recommendations.
- Uses user rating history.
- Identifies similar users.
- Recommends unwatched movies.

9. Applications

- Movie streaming platforms.
- Online entertainment services.
- Personalized content recommendation.
- Movie suggestion websites.

10. Conclusion

The Movie Recommendation Engine is successfully developed using the K-Nearest Neighbour algorithm. It analyzes user ratings, identifies similar users, predicts ratings and recommends movies according to user preferences.
