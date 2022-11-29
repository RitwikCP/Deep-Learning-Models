# IMPLEMENTATION OF ARTIFICIAL NEURAL NETWORKS

![zyro-image (11)](https://user-images.githubusercontent.com/94697656/204504421-e226ef79-6e46-423c-bef0-e47a08881f19.png)


A recurrent neural network (RNN) is a class of artificial neural networks where connections between nodes can create a cycle, allowing output from some nodes to affect subsequent input to the same nodes. This allows it to exhibit temporal dynamic behavior. Derived from feedforward neural networks, RNNs can use their internal state (memory) to process variable length sequences of inputs. This makes them applicable to tasks such as unsegmented, connected handwriting recognition or speech recognition. Recurrent neural networks are theoretically Turing complete and can run arbitrary programs to process arbitrary sequences of inputs. A distinguishing characteristic of recurrent networks is that they share parameters across each layer of the network. While feedforward networks have different weights across each node, recurrent neural networks share the same weight parameter within each layer of the network. That said, these weights are still adjusted in the through the processes of backpropagation and gradient descent to facilitate reinforcement learning.

## GOOGLE STOCK PRICE PREDICTION
### DATASET
The train dataset contains 6 columns and 2300 rows, all in csv format. The test dataset contains 6 columns and 221 rows. Columns include Date,open, high, low,close, and volume.
<img width="972" alt="Screenshot 2022-11-29 at 8 00 48 PM" src="https://user-images.githubusercontent.com/94697656/204557845-a8d71461-761a-40a8-858d-ff30256ce050.png">


### PROBLEM
Given a dataset with a total of 6 dimensions and 2300 records in it, predict the stock price of google for the test set.

### OBJECTIVE
To develop an recurrent neural network that takes into account all train data and predicts stock price of google for the test set.

### MOTIVATION
To learn and implement Recurrent Neural Network using a hands-on approach.

### COMPARISON OF PREDICTED AND ACTUAL STOCK PRICES
![image](https://user-images.githubusercontent.com/94697656/204558560-e9746ef5-1b29-40ba-89eb-460b82310a91.png)

### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)

### CREDIT
[The Ultimate Guide to Recurrent Neural Networks (RNN)](https://www.superdatascience.com/blogs/the-ultimate-guide-to-recurrent-neural-networks-rnn)
