# competitive_gradient_descent
A pytorch implementation of [Competitive Gradient Descent](https://arxiv.org/abs/1905.12103) (CGD) (also see [original implementation](https://github.com/f-t-s/CGD) in Julia).

#### Requirements

Note that the versions are just the ones we used and are not necessarily hard requirements:
```
torch==1.3.1
torchvision==0.4.2
jupyter==1.0.0
tqdm==4.36.1
numpy==1.17.2
matplotlib==3.1.1
```

## CGD on scalar games

![First game](scalar_game1.png)

![Second and third games](scalar_games23.png)

The code for these experiments can be found in: [exp1_scalar_games](exp1_scalar_games/scalar_games.ipynb)

## CGD for training a GAN to fit a 2D gaussian mixture

![Gaussian mixture](gan_gaussianMixture.png)

The code for these experiments can be found in: [exp2_gaussian_mixture](exp2_gaussian_mixture/CGD_vs_GDA_GaussianMixture_GAN.ipynb)


## CGD for training a GAN for image generation on MNIST

The code for these experiments can be found in: [exp3_image_generation](exp3_image_generation)
