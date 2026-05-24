## DL- Convolutional Autoencoder for Image Denoising

### AIM
To develop a convolutional autoencoder for image denoising application.

### Problem Statement and Dataset
This code implements a Denoising Autoencoder using PyTorch to clean noisy images from the MNIST dataset. It uses a convolutional neural network architecture, where the encoder compresses the input image into a lower-dimensional representation, and the decoder reconstructs the original image from this compressed form. To train the model to remove noise, Gaussian noise is added to the clean images, and the network learns to recover the original from the noisy version. The training process uses Mean Squared Error (MSE) as the loss function to measure the reconstruction error and the Adam optimizer to update the model weights. The autoencoder is trained over multiple epochs using mini-batches of data for efficiency. After training, the model's performance is visually evaluated by displaying the original, noisy, and denoised images side by side.

### DESIGN STEPS
#### STEP 1: 
Problem Understanding and Dataset Selection

#### STEP 2: 
Preprocessing the Dataset

#### STEP 3: 
Design the Convolutional Autoencoder Architecture

#### STEP 4: 
Compile and Train the Model

#### STEP 5: 
Evaluate the Model

#### STEP 6: 
Visualization and Analysis

### PROGRAM

#### Name: NITHYA D

### Register Number: 212223240110

```python

```

### OUTPUT :

#### Model Summary

#### Training loss

#### Original vs Noisy Vs Reconstructed Image

### RESULT
Therefore, To develop a convolutional autoencoder for image denoising application executed successfully.
