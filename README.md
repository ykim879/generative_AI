# Generative Adversarial Networks (GANs)
GANs consist of two parts: a generator and a discriminator. 
The generator **creates new data points**, and the **discriminator**** evaluates** them against real data points. Over time, the generator learns to produce data that is increasingly indistinguishable from real data.
Once trained, you can use the generator part of the GAN to create new data by feeding it random noise vectors.
GAN has high-quality and more creative result but difficult to train.
## Training Data Preparation
Prepare a dataset of images representing a wide range of styles you want the AI to learn from. The more diverse your dataset, the more creative and varied the generated styles will be.

## GAN Architecture
Implement a GAN model where the generator learns to create new data, and the discriminator learns to differentiate between generated data and real data from your dataset.
GAN result picture tends to be low quality but it is smoothier to train
## Training Process
During training, the generator receives random noise as input and transforms it into an image. The discriminator then evaluates this image alongside real images from your training set. The training involves backpropagation and optimization steps that gradually improve the generator's ability to produce realistic images.

# Variational Autoencoders (VAEs)
VAEs are another type of generative model that learn a compressed, latent representation of your data. They are particularly good at generating new data points that are similar to the original dataset.

## VAE Architecture
1. **encoder** : compresses the data into a latent space
2. **decoder** : reconstructs the data from the latent space.

The model is trained to minimize the difference between the original and reconstructed images while also regularizing the latent space.
## Data set
https://www.kaggle.com/datasets/agrigorev/clothing-dataset-full
