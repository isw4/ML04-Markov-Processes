### CS 7641 Assignment 4 - Markov Decision Processes

Code can be found at: https://github.com/isw4/ML04-Markov-Processes  
Code taken from: https://github.com/cmaron/CS-7641-assignments (permission to take code given by professor)

## Directories
**environments/**  
    Contains the 2 MDP problems  
**experiments/**  
    Contains code to run experiments on the 2 problems over a range of hyperparameters  
**solver/**  
    Contains code to solve value/policy iteration and Q-learning  
**output/**  
    Contains output graphs and csvs from the experiments

## Installation
Install the pip dependencies using the requirements file and pipenv

## Running
To run the experiments:
~~~
python run_experiments.py --all
~~~

To generate plots from the csv data:
~~~
python run_experiment.py --plot
~~~
