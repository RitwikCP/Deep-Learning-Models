# IMPLEMENTATION OF ARTIFICIAL NEURAL NETWORKS

![zyro-image (11)](https://user-images.githubusercontent.com/94697656/204504421-e226ef79-6e46-423c-bef0-e47a08881f19.png)



A recurrent neural network (RNN) is a class of artificial neural networks where connections between nodes can create a cycle, allowing output from some nodes to affect subsequent input to the same nodes. This allows it to exhibit temporal dynamic behavior. Derived from feedforward neural networks, RNNs can use their internal state (memory) to process variable length sequences of inputs. This makes them applicable to tasks such as unsegmented, connected handwriting recognition or speech recognition. Recurrent neural networks are theoretically Turing complete and can run arbitrary programs to process arbitrary sequences of inputs. A distinguishing characteristic of recurrent networks is that they share parameters across each layer of the network. While feedforward networks have different weights across each node, recurrent neural networks share the same weight parameter within each layer of the network. That said, these weights are still adjusted in the through the processes of backpropagation and gradient descent to facilitate reinforcement learning.

## 
### DATASET
The dataset is called Churn Modelling dataset. It containes over 14 columns and 100000 rows, all in csv format. Columns include Geography, Credit Score, Gender, Age, Tenure, Balance, etc.

<img width="1029" alt="Screenshot 2022-11-29 at 3 12 56 PM" src="https://user-images.githubusercontent.com/94697656/204494727-8b37aa7a-f5c3-426e-b23e-6363395cf1ac.png">


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
