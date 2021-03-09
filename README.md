# Face Generator
This is the fourth project of the Udacity Deep Learning Nanodegree Program.  

## Problem statement
We want to build a **g**enerative **a**dversarial **n**etwork (GAN) that can generate new images of faces.

## Solution
The discriminator is built of a fully connected layer and four convolutional layers with Leaky ReLUs as activation functions. The generator consists of a fully connected layer and three transposed convolutional layers with ReLUs and Tanh as activation functions. The GAN is trained on the [CelebA](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) dataset.  
The modelling is mainly performed with the PyTorch library.  

Some exemplary generated images:  
![Generated Images](/example_generated.png)