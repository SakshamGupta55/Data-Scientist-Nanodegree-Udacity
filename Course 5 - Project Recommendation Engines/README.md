# Project Recommendation Engines

## Summary
In this project, I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles that they will like.


## Files

- Recommendations_with_IBM.ipynb: This is the Jupyter notebook in which Python code is written to make recommendation system for users.

 Code structure is divided into the following parts:

I. Exploratory Data Analysis
  Exploring the data you are working with for the project. 

II. Rank Based Recommendations
Finding the most popular articles based on the most interactions as there are no ratings for any of the articles.

III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. 

IV. Matrix Factorization
A machine learning approach to building recommendations. Using the user-item interactions, a matrix decomposition is built. Using your decomposition, we get an idea of how well we can predict new articles an individual might interact with.

VI Conclusion 
We will finally discuss which methods to use moving forward, and how we might test how well our recommendations are working for engaging users.

## License and Acknowledgement
This is completed as part of the Udacity Data Scientist Nanodegree.
