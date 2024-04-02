# IMDB Recommender System

A recommender system was constructed using the IMDB dataset, serving two primary tasks: Rating Prediction and Would Watch Prediction. The system achieved a mean square error of **3.6** for rating prediction and an accuracy of **78.0%** for would watch prediction.

## Rating Prediction

1. **Baseline Model**: $f(user, item) = \alpha + \beta_u + \beta_i$ (MSE: 3.69)  
   - Where $\alpha$ represents a constant, $\beta_u$ quantifies how much a user tends to rate things above the mean, and $\beta_i$ indicates how much an item tends to receive ratings relative to others.
2. **Latent Factor Model** (MSE: 3.60)

## Would Watch Prediction

1. **Collaborative Filtering** (67.0%)
2. **Bayesian Personalized Ranking** (62.0%)
3. **Logistic Model** (70.0%)
4. **Neural Network** (78.0%)

For a comprehensive analysis, please refer to the [article](https://github.com/Dawson-ma/IMDB-recommender-system/blob/main/Enhancing_Movie_Recommendation_Systems__A_Comprehensive_Analysis_of_IMDB_Data.pdf).

**IMDB Dataset**:  
Aditya Pal, Abhilash Barigidad, and Abhijit Mustafi. Imdb movie reviews dataset. IEEE Dataport, 2020
