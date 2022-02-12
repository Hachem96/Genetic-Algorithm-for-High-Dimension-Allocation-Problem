# Genetic-Algorithm-for-High-Dimension-Allocation-Problem
Implementation of GA in order to solve biobjectives high dimension allocation problem and using ML to predict the values of the tuning parameters
The objective of this project is to use machine learning on a heuristic algorithm to increase its performance in order to solve high dimension allocation problem.

The problem can be solved by maximizing a predefined objective function, minimizing the cost while respecting several complex constraints.
This allocation problem is an industrial problem faced by the engineering in electricity of France (EDF). We have to allocate thousands of tasks to several control-command systems.

In the aim to solve this problem, we implemented genetic algorithm (one of the heuristic methods) and we modified the process of two of its operators (intialization of the population and the mutation). 
The results obtained by these modifications are pretty good and the problem can be solved in acceptable time whatever the instance of the problem is.
In addition, we built a supervised machine learning model (XGBoost) to predict the value of one of genetic algorithm tuning parameters for each different instance of the problem. The input of the models are features extracted from the instances of the problem. 

This could be an introduction in the application of supervised learning to increase the performance of a heuristic method. The results of this idea showed that there is a relation between the target output and the features extracted from the cases study and a machine learning algorithm can find or learn this relation, but the dataset that we had was not enough to get high accuracy. Hence, as a future work we need to collect more data in the aim to increase the accuracy of the model.

Genetic Algorithm: this notebook is the implementaton of Genetic Algorithm to solve the maximum allocation degree objective without the consideration of the cost objective
 
