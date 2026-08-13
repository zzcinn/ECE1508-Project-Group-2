# ECE1508: Learning Data Distribution of Handwritten Digits by Using VAE
## Setup

1. Clone this repository or download the project files.

2. Make sure you have Python installed and Colab.

## Uasge Instructions
Run the notebook cells in order in Colab

Recommended Order:  
1. Setup
2. Load both datasets
3. Train VAE models on MNIST with latent dims of 2, 8, 16
4. Compare MNIST training and test losses
5. Gaussian latent distribution
6. Visualize 2D latent space
7. Compare MNIST reconstruction and generated samples
8. Train VAE models on Fashion MNIST with latent dim of 2, 8, 16
9. Compare lossses, reconstructed images and new generated samples

What the notebook does
1. loads both dataset
2. implements a simple VAE in PyTorch
3. trains models with latent dim of 2, 8, 16
4. evaluates reconstruction loss, KL divergence, and total VAE loss
5. compares the learned latent distribution with a standard Gaussian distribution
6. Visualizes 2D MNIST latent space
7. generates new samples from random latent vectors
8. compares reconstruction quality
