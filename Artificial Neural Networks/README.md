# IMPLEMENTATION OF ARTIFICIAL NEURAL NETWORKS

![zyro-image (11)](https://user-images.githubusercontent.com/94697656/204490914-d4d554d2-44e7-41db-9c47-dd0dc4223ce7.png)


An Artificial Neural Network (ANN) attempts to mimic the network of neurons that make up a human brain so that the computers can have an option to understand things and make decisions in a human-like manner. 
In other words, an ANN is based on a collection of connected units or nodes called artificial neurons, which loosely model the neurons in a biological brain. Each connection, like the synapses in a biological brain, can transmit a signal to other neurons. An artificial neuron receives signals then processes them and can signal neurons connected to it. 
The "signal" at a connection is a real number, and the output of each neuron is computed by some non-linear function of the sum of its inputs. The connections are called edges. Neurons and edges typically have a weight that adjusts as learning proceeds.
The weight increases or decreases the strength of the signal at a connection. Neurons may have a threshold such that a signal is sent only if the aggregate signal crosses that threshold. Moreover, neurons are aggregated into layers. 
Different layers may perform different transformations on their inputs. Signals travel from the first layer (the input layer), to the last layer (the output layer), possibly after traversing the layers multiple times.


## DEEP LEARNING CHURN MODELING
### DATASET
The dataset is called Churn Modelling dataset. It containes over 14 columns and 100000 rows, all in csv format. Columns include Geography, Credit Score, Gender, Age, Tenure, Balance, etc.

### BUSINESS PROBLEM
Given a dataset with a total of 14 dimensions and 100000 records in it, predict whether or not our customer will leave the bank ('Exited' is the dependent variable here).

### OBJECTIVE
To develop an artificial neural network that takes into account all independent variables (the first 13) and predicts whether or not our customer will leave the bank.

### MOTIVATION
To learn and implement Artificial Neural Network using a hands-on approach.

### MODEL ACCURACY SCORE ACHIEVED - 85.9%

### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)

### CREDIT
[The Ultimate Guide to Artificial Neural Networks (ANN)](https://www.superdatascience.com/blogs/the-ultimate-guide-to-artificial-neural-networks-ann)

