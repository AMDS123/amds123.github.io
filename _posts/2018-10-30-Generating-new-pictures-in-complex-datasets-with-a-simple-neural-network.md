---
layout: post
title: "Generating new pictures in complex datasets with a simple neural network"
date: 2018-10-30 01:38:21
categories: arXiv_CV
tags: arXiv_CV
author: Galin Georgiev
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a version of a variational auto-encoder (VAE), which can generate good perturbations of images, when trained on a complex dataset (in our experiments, CIFAR-10). The net is using only two latent generative dimensions per class, with uni-modal probability density. The price one has to pay for good generation is that not all training images are well reconstructed. An additional classifier is required to determine which training image is well reconstructed and generally the weights of training images. Only training images which are well reconstructed, can be perturbed. For good perturbations, we use the tentative empirical drifts of well reconstructed images.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.12478](http://arxiv.org/abs/1810.12478)

##### PDF
[http://arxiv.org/pdf/1810.12478](http://arxiv.org/pdf/1810.12478)

