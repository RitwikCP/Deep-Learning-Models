# IMPLEMENTATION OF BOLTZMANN MACHINE

![BOLTZMANN MACHINE_clipdrop-enhance](https://user-images.githubusercontent.com/94697656/204578818-0c481c41-d55e-487e-baae-ea83e11647b2.png)


A Boltzmann machine is a neural network of symmetrically connected nodes that make their own decisions whether to activate. Boltzmann machines use a straightforward stochastic learning algorithm to discover “interesting” features that represent complex patterns in the database. While this program is quite slow in networks with extensive feature detection layers, it is fast in networks with a single layer of feature detectors, called “restricted Boltzmann machines.” Multiple hidden layers can be processed and trained on efficiently by using the feature activations of one restricted Boltzmann machine as the training dataset for the next. To put it more formally, Boltzmann Machine is a kind of recurrent neural network where the nodes make binary decisions and are present with certain biases. Several Boltzmann machines can be collaborated together to make even more sophisticated systems such as a deep belief network. Coined after the famous Austrian scientist Ludwig Boltzmann, who based the foundation on the idea of Boltzmann distribution in the late 20th century, this type of network was further developed by Stanford scientist Geoffrey Hinton. It derives its idea from the world of thermodynamics to conduct work toward desired states. It consists of a network of symmetrically connected, neuron-like units that make decisions stochastically whether to be active or not. 


## MovieLens 100K Dataset
### DATASET
The dataset is MovieLens 100K dataset. Its is a stable benchmark dataset and contains over 100,000 ratings from 1000 users on 1700 movies, all in csv format.  

### PROBLEM
Given MovieLens 100K dataset, predict movie ratings for the test set.

### OBJECTIVE
To develop a restricted boltzmann machine that takes into account all the given data and predicts ratings accordingly.

### MOTIVATION
To learn and implement restricted boltzmann machine using a hands-on approach.


### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)

### CREDIT
[Boltzmann Machine (BM)](https://www.superdatascience.com/blogs/boltzmann-machine-boltzmann-machine)

