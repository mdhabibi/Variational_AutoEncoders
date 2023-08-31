# Variational AutoEncoders (VAEs) with Keras

This repository offers a collection of notebooks implementing various Variational AutoEncoder (VAE) architectures using the Keras deep learning framework. These implementations span multiple datasets and offer insights into the capabilities of VAEs for tasks such as neural compression and generative modeling.

---

## $\beta$-VAE with MNIST Dataset

This notebook provides a complete pipeline for building, training, and evaluating a $\beta$-Variational Autoencoder ($\beta$-VAE) applied to the MNIST dataset. The MNIST dataset consists of grayscale images of handwritten digits (`0` to `9`), each having dimensions of `28x28` pixels.

### Technologies Used
- Framework: Keras

---

## $\beta$-VAE with CIFAR-10 Dataset

In this notebook, you'll find the necessary code for creating, training, and assessing a $\beta$-VAE on the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 color images of `32x32` pixels, distributed across `10` different classes, each with `6000` images. The primary goal is to employ VAEs for encoding these images into a lower-dimensional latent space and then reconstructing them. The notebook also evaluates the model by comparing the original and reconstructed images.

### Technologies Used
- Framework: Keras

---

## $\beta$-VAE with STL-10 Dataset

This notebook focuses on the application of $\beta$-VAEs to the STL-10 dataset. The STL-10 dataset is tailored for unsupervised and semi-supervised learning methods, featuring `96x96` pixel images across 10 classes. Unlike other similar datasets, STL-10 offers both labeled and unlabeled data, making it ideal for exploring feature learning techniques on higher-resolution images.

### Technologies Used
- Framework: Keras

---

For a more detailed understanding, each notebook includes extensive commentary and evaluation metrics to gauge the model's performance. Feel free to explore!
