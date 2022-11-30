# IMPLEMENTATION OF AUTOENCODERS

![zyro-image (12)](https://user-images.githubusercontent.com/94697656/204704383-d5464381-5894-4b70-a5ed-62be7119aa68.png)


Autoencoders are a specific type of feedforward neural networks where the input is the same as the output. They compress the input into a lower-dimensional code and then reconstruct the output from this representation. The code is a compact “summary” or “compression” of the input, also called the latent-space representation.
An autoencoder consists of 3 components: encoder, code and decoder. The encoder compresses the input and produces the code, the decoder then reconstructs the input only using this code. The aim of an autoencoder is to learn a lower-dimensional representation (encoding) for a higher-dimensional data, typically for dimensionality reduction, by training the network to capture the most important parts of the input image. A sparse autoencoder (SAE) is simply an autoencoder whose training criterion involves a sparsity penalty.

Some of the most important applications of autoencoders are:
1. File Compression: Primary use of Autoencoders is that they can reduce the dimensionality of input data which we in common refer to as file compression. Autoencoders works with all kinds of data like Images, Videos, and Audio, this helps in sharing and viewing data faster than we could do with its original file size.

2. Image De-noising: Autoencoders are also used as noise removal techniques (Image De-noising), what makes it the best choice for De-noising is that it does not require any human interaction, once trained on any kind of data it can reproduce that data with less noise than the original image.

3. Image Transformation: Autoencoders are also used for image transformations, which is typically classified under GAN(Generative Adversarial Networks) models. Using these we can transform B/W images to colored one and vice versa, we can up-sample and down-sample the input data, etc.

## MovieLens 1M Dataset
### DATASET
The dataset is MovieLens 1M dataset. Its is a stable benchmark dataset and contains over 1 million ratings from 6000 users on 4000 movies., all in csv format.  

### PROBLEM
Given MovieLens 1M dataset, predict movie ratings for the test set.

### OBJECTIVE
To develop a sparse autoencoder that takes into account all the given data and predicts ratings accordingly.

### MOTIVATION
To learn and implement autoencoders using a hands-on approach.


### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)

### CREDIT
[Sparse Autoencoder Neural Networks — How to Utilise Sparsity for Robust Information Encoding)](https://towardsdatascience.com/sparse-autoencoder-neural-networks-how-to-utilise-sparsity-for-robust-information-encoding-6aa9ff542bc9)
