---
layout: post
title: "Super-realtime facial landmark detection and shape fitting by deep regression of shape model parameters"
date: 2019-02-09 17:59:07
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Optimization Detection
author: Marcin Kopaczka, Justus Schock, Dorit Merhof
mathjax: true
---

* content
{:toc}

##### Abstract
We present a method for highly efficient landmark detection that combines deep convolutional neural networks with well established model-based fitting algorithms. Motivated by established model-based fitting methods such as active shapes, we use a PCA of the landmark positions to allow generative modeling of facial landmarks. Instead of computing the model parameters using iterative optimization, the PCA is included in a deep neural network using a novel layer type. The network predicts model parameters in a single forward pass, thereby allowing facial landmark detection at several hundreds of frames per second. Our architecture allows direct end-to-end training of a model-based landmark detection method and shows that deep neural networks can be used to reliably predict model parameters directly without the need for an iterative optimization. The method is evaluated on different datasets for facial landmark detection and medical image segmentation. PyTorch code is freely available at https://github.com/justusschock/shapenet

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.03459](http://arxiv.org/abs/1902.03459)

##### PDF
[http://arxiv.org/pdf/1902.03459](http://arxiv.org/pdf/1902.03459)

