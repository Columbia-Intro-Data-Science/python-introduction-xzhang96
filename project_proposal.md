# __Movie Box Office Prediction using IMDb__

#### APMAE 4990 Introduction to Data Science in Industry 

#### Team members: Ben Lai, Cindy Zhang

#### Role: Computing Kernel: Ben Lai, Website design: Cindy Zhang

Tools
--------
Python, JupyterNotebook, Flask

### __Data Source__
https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset

### __Project Description__
How do the movie theaters decide which movies to show given that hundreds of movies are produced every year? And how do we evaluate the goodness of a movie? Box Office is a relatively ideal feature that can answer these questions. The goal of this project is to use the data of over 5000 movies from IMDb to predict the box office of a newly produced movie before it is released in the movie theater so that the movie theater can maximize their profit and the audience can make a better choice of the movies they want to see. The features include the gross, the genre, the IMDb scores, etc. are used to train the model. The box office of a new movie will be predicted using the trained model after providing some information about it by the users of the website.

### __Audience__
Movie theater companies and the audience who already has some information about the upcoming movies, such as the number of Facebook likes of the cast, the genre of the movies, the budget, etc.

### __Algorithms__

## Regression Model
Regression models are used to train the data we obtain from IMDb, and given the data provided by the users, we can get a prediction of the box office using those models.

## Recommendation Engine
A list of recommendation movies can also be shown to the users based on the input data by looking for movies with similar features.

### __Web Application__
Our web application allows the users to input various features of the new movies, and after the algorithms get these variables, the box office will be given to the user.

### __Reference__
The movie data is extracted from IMDb and the complete dataset is obtained from Kaggle: 
https://www.kaggle.com/deepmatrix/imdb-5000-movie-dataset
