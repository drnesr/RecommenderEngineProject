# PROJECT RUBRIC
## Recommendations with IBM

### Code Functionality & Readability

CRITERIA to MEET SPECIFICATIONS
#### Code is functional and passes all tests.

All the project code is contained in a Jupyter notebook or script. If you use a notebook, it demonstrates successful execution and output of the code. All tests have passing remarks.

#### Write code that is well documented and uses functions and classes as necessary.

Code is well documented and uses functions and classes as necessary. All functions include document strings. DRY principles are implemented.

### Data Exploration

#### Explore the data.

Explore the data to understand the number of users, articles, and information about the interactions that take place.

### Create Rank Based Recommendations

#### Create ranked based recommendation model.

Tests will ensure that your functions will correctly pull the top articles. The two functions should pull the top ids and the top names.

### Collaborative Filtering

#### Create the user item matrix.

Create a matrix with users on the rows and articles on the columns. There should be a 1 if a user-article interacted with one another and a zero otherwise.

#### Find similar users needed for user-user collaborative filtering model.

Find similar users needed for user-user collaborative filtering model. Write a function that finds similar users.

#### Make recommendations using user-user based collaborative filtering.

Make recommendations using user-user based collaborative filtering. Complete the functions needed to make recommendations for each user.

#### Improve recommendations using user-user based collaborative filtering.

Improve your original method of using collaborative filtering to make recommendations by ranking the collaborative filtering results by users who have the most article interactions first and then by articles with the most interactions.

#### Provide recommendations for new users.

Provide recommendations for new users, which will not be able to receive recommendations using our user-user based collaborative filtering method.

### Matrix Factorization

#### Perform SVD on user-item matrix.

Perform SVD on user-item matrix. Provides U, Sigma, and V-transpose matrices, as well as an explanation of why this technique works in this case.

#### Perform split of training and testing datasets.

Split the user-item matrix into training and testing segments. Identify the users in the test set that are also in the training.

#### Perform assessment of results.

Perform assessment of the predicted vs. the actual values.

#### Results discussion.

Provide a discussion about the results, as well as a method by which you could test how well your recommendation engine is working in practice.

## Suggestions to Make Your Project Stand Out!
Ways to stand out are to move your notebook into a web application, and blend your code into a class that can be easily used with a web application. You could package your recommendation engine code to be pip installed by others. You could also build out a content based recommendation system using your NLP skills. There are lots of ways to go beyond the rubric for this project!