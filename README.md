# Denoising
they can be used to denoise images quite successfully just by training the network on noisy images. We can create the noisy images ourselves by adding Gaussian noise to the training images, then clipping the values to be between 0 and 1. We'll use noisy images as input and the original, clean images as targets.Here's an example of the noisy images I generated and the denoised images.

https://github.com/udacity/deep-learning/raw/c6b46a0bfcb8d4afcb806174b3923d3ea89ca455/autoencoder/assets/denoising.png

