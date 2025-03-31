# A procedure to nudge outcome selection in games played by algorithms

This code implements a new procedure to nudge the selection of desirable outcomes in games played by algorithms. 

We considergames where players use a Q-learning algorithm to play repeatedly. The innovative feature is to introduce a correlation device: decision makers update their Q-values given the past actions performance and a payoff irrelevant message. Messages, which can be either public or private, are correlated among players. The probability distribution over messages is either stationary (i.e., fixed as input of an algorithm) or time-varying according to a welfare criterion. 

We ask the following questions: do algorithms learn to play correlated equilibria? Does information improve welfare and fairness when algorithms compete? 
This code gives a partial answer to these questions based on simulations. 
