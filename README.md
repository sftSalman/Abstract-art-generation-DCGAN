# Abstruct-art-generation-DCGAN -
![tensorboard](https://github.com/sftSalman/Abstruct-art-generation-DCGAN/assets/33355278/bf8eb23e-ecce-410a-b419-33ed9d1bca82)

Welcome to the GitHub repository dedicated to generating mesmerizing abstract art using the power of Deep Convolutional Generative Adversarial Networks (DCGANs) and the Artbence dataset. This repository provides an all-inclusive framework for creating captivating abstract artworks inspired by the Artbence collection.

The Artbence dataset, meticulously curated and compiled, serves as the foundation for training the DCGAN model. This dataset consists of a vast array of abstract art images, carefully selected to capture the essence of diverse abstract art styles and techniques. By leveraging this unique dataset, users can generate abstract art pieces that embody the essence and beauty of the Artbence collection.


DCGAN (Deep Convolutional Generative Adversarial Network) can be effectively used for generating satellite images. By leveraging deep convolutional neural networks, DCGANs can capture complex spatial dependencies and generate high-quality satellite images that exhibit realistic features.

## Key Components

1. **Generator**: The generator network in a DCGAN for satellite image generation takes random noise as input and gradually upsamples it through convolutional layers. It learns to transform the noise into realistic satellite images by capturing the intricate patterns and structures present in satellite data.

2. **Discriminator**: The discriminator network is responsible for distinguishing between real satellite images and generated images. It takes both real satellite images from a training dataset and generated images from the generator as input. The discriminator uses convolutional layers to extract features and make accurate classifications.

## Training Process

During training, the generator and discriminator networks compete against each other in a game-like setting. The generator aims to produce satellite images that can deceive the discriminator into classifying them as real, while the discriminator strives to correctly classify between real and generated images. This adversarial training process leads to the generator learning to produce increasingly convincing satellite images.

## Loss Functions

DCGANs for satellite image generation typically use loss functions to guide the training process. The generator minimizes the discriminator's ability to differentiate between real and generated images, often employing binary cross-entropy loss. Conversely, the discriminator maximizes its ability to accurately classify real and generated images.

# Key components of this repository include:

# Data preparation:
We have collected the dataset from artbench image folder. We need to customize the dataset for training in gan . The dataset has 60,000 images of artwork from 10 distinctive artistic styles, with 5,000 training images and 1,000 testing images per style.

# DCGAN architecture:
The model comprises a generator network and a discriminator network, designed to capture the intricate details, colors, and visual elements characteristic of abstract art.

# Training procedure:
Detailed instructions, accompanied by code snippets, explain the training process step-by-step. Users can customize various training parameters, including learning rates, batch sizes, and the number of epochs, to fine-tune the DCGAN model according to their specific requirements and computational resources.
here are our parameters 
`LEARNING_RATE = 2e-4 
-BATCH_SIZE = 32
-IMAGE_SIZE = 64
-CHANNELS_IMG = 3
-NOISE_DIM = 100
-NUM_EPOCHS = 10
-FEATURES_DISC = 64
-FEATURES_GEN = 64`

# Art generation:
Once the DCGAN model is trained, users can utilize the trained generator network to generate new abstract art pieces inspired by the Artbence collection. The repository offers example code demonstrating how to generate high-quality abstract images using the trained model. Users can experiment with different noise inputs, control the level of randomness, or generate multiple images in a single run to explore the breadth of artistic possibilities.
Here are generated images :

![generated_18](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/9d0ae263-b04d-4426-9ad3-a32982ff8b01)![generated_13](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/464916f8-239a-42c9-8c5d-2c8dcae8e070)![generated_11](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/4588b50c-6527-4f7d-97eb-d13d2dec5c03)![generated_0](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/a91ea0b5-5141-42ed-ab03-1027aced2a33)![generated_7](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/136a0198-0d8a-40db-b0b0-3787c89c1621)



![generated_14](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/fe52dd8a-1af7-4fb0-85d1-9c2d68aa6929)
