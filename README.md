# Markov Simulation
In this project, customer behaviour in a supermarket is analyzed and simulated in an animation via MCMC

## Table of Contents
- [General info](#general-info)
- [Technologies and Libraries](#technologies-and-libraries)
- [Setup](#setup)


### General info
This project aims to model the flow of customers in a exemplary supermarket via a markov chain.
markov chains are relatively simple models of state-to-state transitions that fulfill the markov property - this means, that the next state of a process depends only upon the present state and not on the events that preceded it. They are used in a wide range of applications like speech recognition, bioinformatics, economics etc. .

To fulfill the markov property in a first-order markov chain, the following assumptions must be met:
1. There is a finite set of states
2. The probabilities of moving between states are fixed and don't change over time (this assumption is a major drawback of markov chains)
3. State accessibility (= you can move from every segment to a different segment without external restriction)
4. Non cyclic transitions

The different sections in the supermarked add up to 5 possible states:
1. drinks
2. dairy
3. spices
4. fruits
5. checkout
#### The transition matrix of the markov-chain
![](transition_monday.png)
#### Example for customer in the supermarket
![](customer_simulation.gif)
### Technologies and Libraries
- Python 3.8
- OpenCV
- pandas
- numpy
- random
- datetime
- time

### Setup
For optimal simulation of customers in a supermarkt, execute the project (MCMC_Animation.py) in **Visual Studio Code** or in your terminal.

