# NeuroFlorist
generation of images with given parameters


In this educational project, a database of 1500 photos of bouquets of flowers was used, which are distributed in 24 classes with two features: color and variety of flowers.
Various configurations of neural networks were tested: combinations of conditional autoencoders with conditional GANs with fully connected layers, convolutional layers, combined.
The best results are obtained using CVAE with fully connected layers. The network exhibits overfitting due to the small number of examples for each class.
