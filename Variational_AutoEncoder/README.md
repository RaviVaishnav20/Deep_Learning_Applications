# Variational Auto Encoder

## VAE is architecture we are going to implement

![VAE architecture](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Variational_AutoEncoder/VAE_architecture.png)

## Loss Function (Sum of Binary Cross Entropy loss and KL divergence Loss
#### $Loss = -E[\log P(X | z)]+D_{K L}[N(\mu(X), \Sigma(X)) \| N(0,1)]$
#### $D_{K L}[N(\mu(X), \Sigma(X)) \| N(0,1)]=\frac{1}{2} \sum_{k}\left(\exp (\Sigma(X))+\mu^{2}(X)-1-\Sigma(X)\right)$

## Results

#### Reconstructed Image after first epoch
![Reconstructed Image 1](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Variational_AutoEncoder/reconstruction_1.png)

#### Reconstructed Image after fifty epoch
![Reconstructed Image 2](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Variational_AutoEncoder/reconstruction_50.png)

#### Sample Image generated using Decoder at first epoch
![Reconstructed Image](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Variational_AutoEncoder/sample_1.png)

#### Sample Image generated using Decoder at 50 epoch
![Reconstructed Image](https://github.com/RaviVaishnav20/Deep_Learning_Applications/blob/master/Variational_AutoEncoder/sample_50.png)



