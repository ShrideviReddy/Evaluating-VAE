# VAE-Performance (Work in progress)
## Motivation:
Hyperparameter tuning is important for good performance. In this project I am trying to check the performance of Variational autoenocder with different latent dimensions.
I have implemented first part with the latent dimension equal to 200. In the next part, I will be using latent dimension equal to 150 and 100.  
## Dataset: 
CelebA
## Variational autoencoder Introduction:
A variational autoencoder (VAE) provides a probabilistic manner for describing an observation in latent space.
Thus, rather than building an encoder which outputs a single value to describe each latent state attribute, we'll formulate our encoder to
describe a probability distribution for each latent attribute.
Following diagram shows flow of Variational Autoenocder:
![VAE Flow Diagram](https://github.com/ShrideviReddy/VAE-Performance/blob/master/results/VAE-model.PNG)

## Results:
### For Z = 200 and epochs = 25
![VAE-1](https://github.com/ShrideviReddy/VAE-Performance/blob/master/results/VAE-25%20epochs.PNG)
### For Z = 200 and epochs = 50
![VAE-2](https://github.com/ShrideviReddy/VAE-Performance/blob/master/results/VAE-50%20epochs.PNG)
