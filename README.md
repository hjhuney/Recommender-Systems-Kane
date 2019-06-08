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



