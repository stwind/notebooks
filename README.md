# Notebooks

Bookkeeping some notebooks

## Preperation

### Requirements

* [pyenv](https://github.com/pyenv/pyenv)

### Setup

```sh
$ pyenv virtualenv 3.7.2 notebooks
$ pyenv activate notebooks
$ pip install --upgrade pip
$ pip install -r requirements.txt
```

## Contents

* [Exploring MNIST with T-SNE](./mnist-tsne.ipynb)
* [Drawing Normal Distribution](./normal-dist.ipynb)
* [Restricted Boltzmann Machines implemented in numpy](./rbm-raw.ipynb)
* [Restricted Boltzmann Machines implemented in Tensorflow 2](./rbm-tf.ipynb)
* [Fashion MNIST with UMAP](./umap-fashion-mnist.ipynb)
* [VAE on MNIST with Pyro](./pyro_vae.ipynb)
* [VAE on Fashion MNIST with Pytorch](./pytorch_vae.ipynb)
