# Denoising Autoencoder for Fashion MNIST

This project implements a Denoising Autoencoder using TensorFlow for the Fashion MNIST dataset. The model aims to remove noise from images using an autoencoder architecture.

## Project Overview

The project includes the following components:

1. **Data Preprocessing**: The Fashion MNIST dataset is loaded, normalized, and prepared with added noise for training and testing.

2. **Autoencoder Model**: An autoencoder model is defined with an encoder and decoder architecture for denoising images.

3. **Model Training**: The model is trained on the noisy images and evaluated on the test set.

4. **Results Visualization**: Original, noisy, and denoised images are displayed for visual comparison.

5. **Model Evaluation**: The model's performance is evaluated based on the test and train loss.

## Instructions

To run the project:

1. Ensure you have TensorFlow and other necessary libraries installed.
2. Run the provided Python script containing the code.
3. Check the denoised images and the model's performance metrics.

## File Structure

- `Denoising_Variational_Autoencoder_for_Fashion_MNIST.ipynb`: Jupyter Notebook script containing the project code.
- `README.md`: This file providing an overview of the project.

## Dependencies

- TensorFlow
- NumPy
- Pandas
- Matplotlib

## Results

The model successfully denoises the Fashion MNIST images, as demonstrated by the comparison of noisy, original, and reconstructed images.

## Acknowledgements

- The Fashion MNIST dataset is used for this project.
- TensorFlow library is utilized for building and training the model.

For more details, refer to the project code in `Denoising_Variational_Autoencoder_for_Fashion_MNIST.ipynb`.