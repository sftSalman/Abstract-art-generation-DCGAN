# Abstruct-art-generation-DCGAN
![tensorboard](https://github.com/sftSalman/Abstruct-art-generation-DCGAN/assets/33355278/bf8eb23e-ecce-410a-b419-33ed9d1bca82)

Welcome to the GitHub repository dedicated to generating mesmerizing abstract art using the power of Deep Convolutional Generative Adversarial Networks (DCGANs) and the Artbence dataset. This repository provides an all-inclusive framework for creating captivating abstract artworks inspired by the Artbence collection.

The Artbence dataset, meticulously curated and compiled, serves as the foundation for training the DCGAN model. This dataset consists of a vast array of abstract art images, carefully selected to capture the essence of diverse abstract art styles and techniques. By leveraging this unique dataset, users can generate abstract art pieces that embody the essence and beauty of the Artbence collection.

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

![generated_18](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/9d0ae263-b04d-4426-9ad3-a32982ff8b01)


![generated_0](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/a91ea0b5-5141-42ed-ab03-1027aced2a33)


![generated_14](https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/fe52dd8a-1af7-4fb0-85d1-9c2d68aa6929)
