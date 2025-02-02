# MNIST Generation Project

## Overview

The MNIST Generation Project leverages Generative Adversarial Networks (GANs) to create realistic images of handwritten digits. The project utilizes the MNIST dataset, which comprises 70,000 images of handwritten digits (0-9). This dataset is a standard benchmark for evaluating image processing and machine learning algorithms.

By training a GAN on this dataset, the project aims to explore the capabilities of neural networks in generating synthetic data that closely resembles real handwritten digits.

## Results

After training, the generated images will be stored in the `outputs` folder. The quality of the generated digits typically improves with more training epochs. To enhance the model's performance, you can experiment with various techniques, including:

- **Hyperparameter Tuning**: Adjust parameters such as learning rate, batch size, and the number of epochs.
- **Model Architecture Modifications**: Experiment with different architectures for the generator and discriminator.
- **Data Augmentation**: Apply techniques to augment the training dataset, which can lead to better generalization.

## Generated Images

### Epoch 50
Here is an example of a generated image at epoch 50:

![Generated Image at Epoch 50](https://github.com/alirzx/MNIST-Generation-Using-GAN/blob/main/outputs/gan_generated_epoch_50.png?raw=true)

This image showcases the GAN's ability to generate realistic handwritten digits. As the training progresses, you can expect to see improvements in the quality and diversity of the generated images.

