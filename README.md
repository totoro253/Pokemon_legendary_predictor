## Introduction
Hey guys!
Today I learned about data mining in Python. 
I used a CSV file with a lot of different pokemons including different generations.
## What is data mining?
Imagine you have a CSV with a lot of pokemons. I learned by using data mining whether a pokemon was a legendary or not.
I used the method to split my data intro regular data and training data.
For example: legendary or not, x is used in the prediction and  y outcome i want to predict.
## What was the outcome?
My outcome was that the accuracy was 0.965.
Which means that roughly 96% chance you could tell succesfully whether a pokemon was a legendary or not.
## Why train and split data?
The model will take for example Charmander , you  know that it is not a legendary pokemon although you can use a select group of pokemon to test whether the pokemons are legendary or not. You know probarbly the answer although it can be usefull to train a selected part of the data to test accuracy.
## Future
In the future I want to learn about the confusion matrix and specificity.
For now I am content with knowing the legendary pokemon accuracy although in the future I want to answer questions such as "How many cases are pokemon not legendary?"

## Theory for the future
During these analyses I learned a couple of new terms and learned about testing and training models.
Just in case I want to share the theory which will maybe be applied in the future or I am currently learning to understand.
### Specificity
Meaning describing the selected elements are truly negative, simplified: How many pokemons are truly not legendary
Usefull source: https://towardsdatascience.com/sensitivity-specificity-and-meaningful-classifiers-8326738ec5c2
### Bootstrap
Bootstrap randomly performs row sampling and feature sampling from the dataset to form sample datasets for every model. 
