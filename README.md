# Abstruct-art-generation-DCGAN -



https://github.com/sftSalman/Abstract-art-generation-DCGAN/assets/33355278/41159e89-21f5-42e2-b662-89cc37148f7e



Welcome to our GitHub repository! Here, we focus on creating mesmerizing abstract art using powerful Deep Convolutional Generative Adversarial Networks (DCGANs) and the Artbence dataset. This framework allows you to easily generate captivating abstract artworks inspired by the diverse Artbence collection.

The Artbence dataset serves as the foundation for training the DCGAN model. It contains carefully curated abstract art images, representing various styles and techniques. With this dataset, you can create abstract art that truly reflects the essence and beauty of the Artbence collection.




To achieve the generation of mesmerizing abstract art, we employ Deep Convolutional Generative Adversarial Networks (DCGANs). DCGANs are a powerful class of neural networks designed specifically for image synthesis tasks. They consist of two networks: a generator and a discriminator, which work in tandem to produce high-quality and realistic image.

## Training Process

During training, the generator and discriminator networks compete against each other in a game-like setting. The generator aims to produce satellite images that can deceive the discriminator into classifying them as real, while the discriminator strives to correctly classify between real and generated images. This adversarial training process leads to the generator learning to produce increasingly convincing satellite images.

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






