# This folder is about codes of synchronization project on Directed networks
# Directed acyclic graph(DAG) Network, FeedForward loops:
This code is a function that gets an undirected graph and transforms it into a DAG network (Directed acyclic network)
It gets an adjacency matrix as input and returns a new adjacency matrix. This new network has only one leader node that has zero in_degrees
the new graph is connected based on the directed networks definition.
https://www.researchgate.net/publication/281542584_Are_feedback_loops_destructive_to_synchronization
# Ml_prediction_test:
This undertaking is a basic experiment aimed at assessing the feasibility of predicting the order parameter within the synchronization model of a first-order Kuramoto model. This model is numerically derived across one hundred Balanced Directed Smallworld networks, each with a size of 500. each network is solved via the RK4 method on 100 different initial phases. targets are order parameters, coefficients of variation of order parameters, and the ratio of order parameters in every network. features are basic mathematical structure characteristics of networks (like clustering coefficients, average shortest path, diameter, and number of feedforward loops or feedback loops)
