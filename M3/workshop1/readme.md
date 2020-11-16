# M3 - Deep Learning Workshop 1


In this workshop will revisit the [AirBnb dataset](http://data.insideairbnb.com/denmark/hovedstaden/copenhagen/2020-06-26/data/listings.csv.gz) that we used in M1. 

## 1. Build a neural net for price prediction.

Your job is to build a feed-forward network using Keras to predict the price.
Can you beat the performance of other models that we explored in M1 (using the same set of independent variables)? Start with a "simpler" baseline model using 1 2 layers only (one input layer one output layer).

## 2. Tune the network.

Experiment with different set-ups changing e.g.:

- number of neurons
- number of layers 
- number of epochs and batch size
- activation functions (reasonable choices)
- optimizers and losses (again: reasonable choices)

Use the Keras documentation and community sources to identify best practices. However, do not spend hours on grid search!

## 3. Prevent overfitting

This part is related to 2. Explore the training process (over the epochs). Explore and describe 2 common approaches used to prevent overfitting in deep feed-forward neural nets.

Try to implement them on your data.


## R example

* [Html](https://sds-aau.github.io/SDS-master/M3/exercises/ANN_workshop.nb.html)
* [Python notebook RJ](https://nbviewer.jupyter.org/github/SDS-AAU/SDS-2020/blob/master/M3/workshop1/M3_W1_AirBnb.ipynb)