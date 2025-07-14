The purpose of this project was to apply stochastic optimization to build a recommendation engine. It is based on Netflix's competition in 2006, relying on matrix factorization techniques.
- We generated 2 matrices: one for user-embeddings and one for movie-embeddings, as well as 2 bias vectors. 
- We implemented the stochastic gradient descent with L2 regularization to solve the optimization problem and recover a full and low-rank rating matrix. 
- We can now also analyze similar users and movies based on their embedding vectors.
- We implemented a regularization term to enhance fairness in the predicted ratings, so that our algorithm reduces bias between genders while training the model.

All mathematical formulations are included in the report, and the algorithms were implemented using MATLAB.
(There is a small mistake in the fairness implementation).
