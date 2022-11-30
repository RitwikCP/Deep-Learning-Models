# CASE STUDY - MAKING A HYBRID DEEP LEARNING MODEL

![zyro-image (12)](https://user-images.githubusercontent.com/94697656/204706787-04190240-39e7-46e2-b385-b246055dd95c.png)

As the name suggests, this project is about combining two deep learning models, i.e., the Artificial Neural Network and the Self-Organizing Map. Credit card applications dataset is used to identify the frauds, but the main idea here is to make an advanced deep learning model so that probability that each customer cheated can be predicted, and to do this; one needs to go from unsupervised to supervised deep learning.
The project consists of two parts, in the first part, unsupervised deep learning branch of our hybrid deep learning model is made, and then in the second part, the supervised deep learning branch is made that will result in the hybrid deep learning model composed of both unsupervised and supervised deep learning.
As mentioned before, the Credit Card Applications dataset is used which contains all the credit card applications from the different customers of a bank and the self-organizing map is used exactly as before to identify the fraud. But here we entend that project, by using the results of this self-organizing map to combine our unsupervised deep learning model to a new supervised deep learning model that will take as input the results given by our SOM. The challenge is to obtain a ranking of the predicted probabilities that each customer cheated. We will get very small probabilities because the SOM identified only a few frauds, but that doesn't matter. The main goal is to get this ranking of the probabilities.

## CREDIT CARD APPLICATIONS DATASET

### DATASET
The dataset is called Credit Card Applications dataset. It containes over 15 columns and 690 rows, all in csv format. The columns are already encoded and probably contain information that may help the model to predict which of them represents fraud.
<img width="846" alt="Screenshot 2022-11-29 at 8 35 18 PM" src="https://user-images.githubusercontent.com/94697656/204566398-4716acc3-b13e-4a48-8a45-f46798c2e315.png">


### PROBLEM
Given a dataset with a total of 15 dimensions and 690 records in it, predict whether or not our the credit card represents fraudulent transaction or not. Moreover, obtain a ranking of the predicted probabilities that each customer cheated.

### OBJECTIVE
To develop a self organizing map that takes into account all given data and predicts whether or not the credit card is associated with fraud. In other words, by the end of it we have to give the explicit list of the customer who potentially cheated and also giev a ranking of the predicted probabilities that each customer cheated.

### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)

### CREDIT
[Mega Case Study](javatpoint.com/keras-mega-case-study)


### MOTIVATION
To learn and implement a hybrid deep learning model using a hands-on approach.
