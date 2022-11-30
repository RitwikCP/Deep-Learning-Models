# IMPLEMENTATION OF CONVOLUTIONAL NEURAL NETWORKS


![zyro-image (12)](https://user-images.githubusercontent.com/94697656/204496578-367946c2-a4b8-4358-b3e0-8f881436501e.png)


A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm that can take in an input image, assign importance (learnable weights and biases) to various aspects/objects in the image, and be able to differentiate one from the other. The pre-processing required in a ConvNet is much lower as compared to other classification algorithms. While in primitive methods filters are hand-engineered, with enough training, ConvNets have the ability to learn these filters/characteristics. The architecture of a ConvNet is analogous to that of the connectivity pattern of Neurons in the Human Brain and was inspired by the organization of the Visual Cortex. Individual neurons respond to stimuli only in a restricted region of the visual field known as the Receptive Field. A collection of such fields overlap to cover the entire visual area.


## DOG VS. CATS UISNG CNN
### DATASET
The dataset containes over 10000 images of cats and dogs. Almost 1000 test images and almost 4000 train images for dogs and cats each.
The dataset can be downloaded from [here](https://www.superdatascience.com/pages/deep-learning) (Part 2: Convolutional Neural Networks (CNN), Datasets & Templates).
Few images from the dataset are:

![cat 4052](https://user-images.githubusercontent.com/94697656/204501232-e805c236-615d-4570-bdcc-ee5d9a840bc0.jpg)
![dog 4056](https://user-images.githubusercontent.com/94697656/204501295-c8fd8f0c-0292-43a6-a40e-616aa0f73892.jpg)
![cat_or_dog_1](https://user-images.githubusercontent.com/94697656/204503341-74773b18-2bcf-4eb0-9755-0a21366fa24f.jpg)
![cat_or_dog_2](https://user-images.githubusercontent.com/94697656/204503113-fe9a139f-db6b-4fe4-ba00-48adf83aca28.jpg)


### PROBLEM
Given a dataset with a total of around 8000 images (almost 4000 for dogs and 4000 for cats) and given a test image, predict whether the image is of a dog or of a cat.

### OBJECTIVE
To develop an convolutional neural network that takes into account all the images into consideration and predicts whether the given image is of a dog or a cat.

### MOTIVATION
To learn and implement Convolutional Neural Network using a hands-on approach.

### MODEL ACCURACY SCORE ACHIEVED - 85.9%

### TECH/FRAMEWORK USED
[Jupyter Notebook](https://jupyter.org/)

### CREDIT
[The Ultimate Guide to Convolutional Neural Networks (CNN)](https://www.superdatascience.com/blogs/the-ultimate-guide-to-convolutional-neural-networks-cnn)
