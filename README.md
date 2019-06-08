# Basics of Recommender Systems 

Notes From Frank Kane's Recommender Systems Course

## Types of Recommenders

* Explicit. User assigns items a rating. Data can be sparse. Sometimes users have different standards. 

* Implicit / Click Data. Less issues with sparsity, but susceptible to fraud due to bots. 

* Implicit / Purchase Data. Very good because difficult to game. 

* Implicit / Consumption Data. How long you spend watching a video (e.g. YouTube). Generally pretty good. 

## Top-N Recommenders

Predicting top 5 or top 10 recommendations. Typically start with big NoSQL database like Mongo, generate recommendation candidates, candidate ranking, filtering (e.g. items already purchased / viewed). 

# Evaluation

## Mean Absolute Error (MAE)

Find absolute value of difference between predicted rating and actual rating. Sum error of all ratings up and divide by <i>n</i>. 

## Root Mean Squared Error (RMSE)

Sum up square of errors and divide by n. 

## Top-N Hit Rate

Add up all hits versus users. 

## Leave One Out Cross Validation

Compute top end recommendations and intentionally remove one item from user's training data, then test rec system's ability to  recommend that item. 

## Average Recirpocal Hit Rate (ARHR)

Sum up reciprocal rate of each hit. Rank 3 equals 1/3. Rank 1 equals 1. Rank 5 equals 1/5. 

## Cumulative Hit Rate

## Rating Hit Rate

## Coverage

Percentage of <user, item> pairs that can be predicted. 

