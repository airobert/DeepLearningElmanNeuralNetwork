# deepLearningPlayground

This is a case study of Elman Neural Network for the analysis of the trajectory of the E-puck robots.

There are three layers

1) The first layer has two inputs i =2

2) The second layer has 5 hidden neurons

3) The third layer has one output neuron.

Each neuron of the hidden and the output layers has a bias.

The network has 46 parameters.

The activation function used in the hidden and the output neurons is the logistic sigmoid function = 

sig x = 1 / (1 + e^(-x)) 

if the output is less than 0.5, it is a model. Otherwise, it is an agent.

The network's memory (hidden neurons) is reset after each judgment.

==========================

e-puck is a robot that has two wheels. 


==========================

in each study, we use 10 robots and one replica = 11 individuals.

initial positions were generated randomly.

=========================

we will study the agent's linear and angular speed sequences and calculate the model's fitness. 


TL paper: 4.5 Analysis of Generated Classifiers.

