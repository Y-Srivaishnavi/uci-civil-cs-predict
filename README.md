# Predict Compressive Strength using random Forest Regresssor

## Inspiration
This project served as the base for my research on using regression to predict compressive strength. 

## What it does
It saves experimentation time for civil engineers by estimating its target based on relevant input features such as cement content, water content, etc. 

## How we built it
The project is built entirely in Python. It uses the Pandas and NumPy modules for data manipulation, Matplotlib and Seaborn for visualization, and scikit-learn for preprocessing and model training. 

## Challenges we ran into
Our biggest challenge was to overcome overfitting as well as underfitting by finding the right train-test split to train the model. 

## Accomplishments that we're proud of
The model achieves a best R2 of 92, which is great for a small dataset with no feature reduction. 

## What we learned
Find a model for your data, not the other way around. 

## What's next for Predicting Compressive Strength with Random Forest Regressor
Improving model scores with more sophisticated ensembles like LightGBM, or ensembles that allow for more model diversity. 
