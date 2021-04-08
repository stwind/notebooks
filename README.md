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
* [Neural Cellular Automata](./neural_ca.ipynb)
* [Neural Cellular Automata Textures](./neural_ca_textures.ipynb)
* [Semantic Segmentation with U-Net](./unet_vanilla.ipynb) [![](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/stwind/notebooks/blob/master/unet_vanilla.ipynb)
* [Generalizable Data-free Objective for Crafting Universal Adversarial Perturbations](./gd_uap.ipynb)
* [Vanilla Style Transfer](./style_transfer_vanilla.ipynb)
* [Semantic Segmentation with U-Net++](./unetplusplus.ipynb)
* [Semantic Segmentation with U2-Net](./u2net.ipynb)
* [Segmentation And Matting with OpenCV](./cv_seg_matting.ipynb)
* [Sorting and UMAPing Ukiyo-e faces](./umap_hdbscan_ukiyoe_face.ipynb)
* [Sorting and UMAPing Kaokore](./umap_hdbscan_kaokore.ipynb)
* [Generating Images with Pretrained Stylegan2-Ada](./stylegan2_ada_gen.ipynb)
* [Object Detection with detectron2 on PeopleArt](./detectron2_peopleart.ipynb)
* [Organize Images by Similarity](./image_similarity_architectures.ipynb)
* [Retrain VGG16 For Image Similarity Sort With UMAP, Geomloss and LapJV](./vgg16_umap_geomloss_lapjv_sketches.ipynb)
