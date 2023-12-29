# Fashion-GAN: Generating Diverse Fashion Images with Deep Convolutional Generative Adversarial Networks

## Overview

This project harnesses the power of Generative Adversarial Networks (GANs) to try to produce conventional and novel images of various clothing and apparel items. It leverages the Fashion-MNIST dataset, a collection of 60,000 grayscale images (28x28 pixels) spanning 10 fashion categories, commonly used for image classification tasks. This project explores the potential of GANs to generate creative fashion designs, offering a unique twist on traditional classification approaches.

## Dataset and Model Architecture

Dataset:

    Fashion-MNIST:
        60,000 28x28 grayscale images
        10 fashion categories (e.g., shoes, jeans, etc.)
        Available within TensorFlow Keras API datasets

Model Architecture:

    Generator:
        7-layer Deep Convolutional GAN (DCGAN) architecture
        Alternating feed-forward and convolutional layers
        Leaky ReLU activation for feed-forward layers
    Discriminator:
        6-layer DCGAN architecture
        Alternating feed-forward and convolutional layers

## Key Features:

    GAN-Based Image Generation: Trains a GAN to produce realistic fashion images.
    Fashion-MNIST Exploration: Leverages a dataset commonly used for classification in a generative context.
    Leaky ReLU Experimentation: Explores Leaky ReLU's effectiveness in model performance.


<sup>For in-depth analysis of hyperparameter tuning experiments and future research directions, refer to the comprehensive [report]</sup>

[report]: https://www.mediafire.com/file/sxynksu2830a83b/Fashion_GAN.pdf/file
