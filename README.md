# IMDB-recommender-system

A recommender system was construch using the IMDB dataset.  
The recomender system has two tasks: Rating Predition and Would Watch Prediction  

## Rating Prediction:
1. $f(user, item) = \alpha + \beta_u + \beta_i$ (MSE: 3.69)  
where $\alpha$ is a constant, $\beta_u$ is how much does this user tend to rate things above the mean, and $\beta_i$ is how much does this item tend to receive  ratings than others.
2. Latent Factor Model (MSE: 3.60)

## Would watch Prediction:
1. Collaborative filtering (67.0%)
2. Bayesian Personalized Ranking (62.0%)
3. Logistic model (70.0%)
4. Neural Network (78.0%)

For more detail, please read [article](https://github.com/Dawson-ma/IMDB-recommender-system/blob/main/Enhancing_Movie_Recommendation_Systems__A_Comprehensive_Analysis_of_IMDB_Data.pdf).

IMDB Dataset:
Aditya Pal, Abhilash Barigidad, and Abhijit Mustafi. Imdb movie
reviews dataset. IEEE Dataport, 2020
