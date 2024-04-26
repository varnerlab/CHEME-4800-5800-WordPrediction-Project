# CHEME-4/5800 Word Prediction Project
Word prediction using k-grams project for CHEME 4/5800

## Description
One of the unbelievable features of large language models is the ability to generate a convincing text response given a prompt. However, before the massive Neural Networks that underly large language models, which are out of reach to everyone except the most resource-rich private companies, researchers approached this problem using Markov models. 
* Design and implement a program to predict the probability of an output sequence that can occur using k-gram states (a collection of k-input words) using a Markov Model. This project will construct a model and compute the probability of observing an output sequence by analyzing the [Cornell movie review database](https://www.cs.cornell.edu/people/pabo/movie-review-data/) used previously in the course. I've downloaded the movie review data to the [data folder](data).
* To test your program, split the movie review data into training and test sets and compute how well your program performs on the test set for different values of k, i.e., the probability of correct prediction given a collection of one-word inputs, two-word inputs, etc. 
