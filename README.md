# Hyperbolic (variational) autoencoders for recommender systems
Accompanying code for the paper

## Data
To reproduce our code, please put the data files in the following order:

data
  -recvae
    --ml20m
  -troublinganalysis
    --mvae
      ---netflix
    --neumf
      ---ml1m
      ---pinterest

Also, please install geoopt package (https://github.com/geoopt) for Riemannian optimization

## Wandb
In our experiments, we have used wandb framework for result tracking. Our test scripts are based on wandb configs.

## Acknowledgments
In our code we have used the following repositories:
-https://github.com/oskopek/mvae
