# DL- Convolutional Autoencoder for Image Denoising

## AIM
To develop a convolutional autoencoder for image denoising application.

## DESIGN STEPS

1. Data Preparation – Load the MNIST dataset and normalize the images.

2. Noise Addition – Add random Gaussian noise to the images for training.

3. Model Design – Build a Convolutional Autoencoder with encoder and decoder layers.

4. Training Process – Use MSE Loss and Adam Optimizer to minimize reconstruction error.

5. Visualization – Display original, noisy, and denoised images to evaluate performance.



### OUTPUT

### Model Summary

<img width="727" height="457" alt="image" src="https://github.com/user-attachments/assets/3724f7c5-3b95-4897-bbf7-b0ca17a1a8af" />

## Original vs Noisy Vs Reconstructed Image

<img width="1374" height="609" alt="image" src="https://github.com/user-attachments/assets/9f3e1244-e6b4-45d7-a2e6-d8e457bdfa79" />


## RESULT

The Convolutional Autoencoder model was successfully trained on the MNIST dataset for image denoising.

After training for 5 epochs, the loss stabilized around 0.1120, showing good reconstruction performance.

The model effectively removed noise from the test images, and the denoised outputs closely resembled the original images.
