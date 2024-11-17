# Handwritten Digit Generation

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) designed to generate realistic handwritten digits. By leveraging a generator-discriminator architecture, the DCGAN learns to produce digit images resembling those in datasets like MNIST.

# MNIST Dataset

A dataset containing 70,000 grayscale images of handwritten digits, each of size 28x28 pixels. It is divided into 60,000 training images and 10,000 test images, with labels ranging from 0 to 9

# Preprocessing
- Resized the images
- Converted to Tensors
- Normalized the mean and standard deviation of each channel
  
# Approach

- Built the Discriminator
- Built the Generator
- Initialized weights to prevent mode collapse and weight explosion
- Preprocessed the Images
- Built a custom train loop


# Test Results
![Screenshot 2024-11-16 090806](https://github.com/user-attachments/assets/70ccac87-d24e-44e5-9acb-5e7e31debf1c)
