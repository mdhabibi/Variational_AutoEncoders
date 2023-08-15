# Variational AutoEncoders (VAEs)
This repository contains implementations of various Variational AutoEncoder (VAE) models using the Keras deep learning framework. The models are applied to different datasets and feature diverse architectures to explore and demonstrate the potential of VAEs in the fields of neural compression and generative modeling.

# End-to-End $\beta$-VAE_MNIST
$\beta$-Variational Autoencoder of MNIST in Keras

The provided script includes the required code for creating, training, and evaluating a **$\beta$-Variational Autoencoder ($\beta$-VAE)** using the MNIST dataset. The MNIST dataset comprises grayscale images of handwritten digits ranging from `0` to `9`, each with dimensions of `28` by `28` pixels. The **Keras** framework was employed in this project.


# End-to-End $\beta$-VAE_CIFAR10
$\beta$-Variational Autoencoder of CIFAR10 in Keras

The provided script includes the required code for creating, training, and evaluating a **$\beta$-Variational Autoencoder ($\beta$-VAE)** using the CIFAR10 dataset. The CIFAR-10 dataset consists of 60,000 `32x32` color images in `10` classes, with `6000` images per class. Our primary aim is to train a VAE to encode these images into a lower-dimensional latent space, and then reconstruct the original images from this encoded representation. The notebook also delves into the evaluation of the trained model, comparing the original and reconstructed images for a comprehensive understanding of the model's performance. The **Keras** framework was employed in this project.


# beta-VAE-STL10
Variational Autoencoder of STL10 with Keras

This notebook explores the use of **$\beta$-Variational Autoencoders ($\beta$-VAEs)** for the **STL-10 dataset**. This dataset is designed for evaluating unsupervised and semi-supervised learning algorithms, offering 10 classes of `96x96` pixel images. Unlike similar datasets, STL-10 provides both labeled and unlabeled images, making it an excellent benchmark for exploring feature learning techniques in higher-resolution data.
