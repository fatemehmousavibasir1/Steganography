# Deep Learning-based Image Steganography

## Overview:

This project implements an image steganography system using deep learning techniques, specifically convolutional neural networks (CNNs). The goal of steganography is to embed a secret image inside a cover image in a way that the output (stego image) is visually indistinguishable from the original, yet can later be decoded to reveal the hidden content.

## Key Features:

End-to-End Steganography Pipeline: Includes both the encoder (for embedding) and decoder (for revealing) networks.

Dataset Handling: Automatically organizes data into training, validation, and test sets.

Model Architecture: Utilizes Keras/TensorFlow-based convolutional neural networks with skip connections and upsampling layers.

Visualization: Includes functions to visualize input, encoded, and decoded outputs.

Evaluation: Uses loss functions and visualization to assess quality of embedding and decoding.

## Project Structure:

DATASET_DIR: Base dataset directory, includes all images.

TRAIN_DIR, TEST_DIR, VALID_DIR: Directories created and populated automatically from dataset.

Training set: 1000 images

Test set: 500 images

Validation set: 200 images

Model Description:

The model takes two inputs:

Cover image: The visible image.

Secret image: The image to hide.

Outputs a stego image.

A second network decodes the stego image to retrieve the hidden secret.

Encoder and decoder are both implemented using deep convolutional architectures.

## Technologies Used:

Python

Keras and TensorFlow

NumPy, Matplotlib

Google Colab for training

TQDM for progress visualization

## Applications:

Secure image sharing

Digital watermarking

Information hiding in plain sight

Enhancing privacy in communication systems
