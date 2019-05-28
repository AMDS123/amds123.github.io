---
layout: post
title: "SpecNet: Spectral Domain Convolutional Neural Network"
date: 2019-05-27 00:44:14
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Inference Recognition
author: Bochen Guan, Jinnian Zhang, William A. Sethares, Richard Kijowski, Fang Liu
mathjax: true
---

* content
{:toc}

##### Abstract
The memory consumption of most Convolutional Neural Network (CNN) architectures grows rapidly with increasing depth of the network, which is a major constraint for efficient network training and inference on modern GPUs with yet limited memory. Several studies show that the feature maps (as generated after the convolutional layers) are the big bottleneck in this memory problem. Often, these feature maps mimic natural photographs in the sense that their energy is concentrated in the spectral domain. This paper proposes a Spectral Domain Convolutional Neural Network (SpecNet) that performs both the convolution and the activation operations in the spectral domain to achieve memory reduction. SpecNet exploits a configurable threshold to force small values in the feature maps to zero, allowing the feature maps to be stored sparsely. Since convolution in the spatial domain is equivalent to a dot product in the spectral domain, the multiplications only need to be performed on the non-zero entries of the (sparse) spectral domain feature maps. SpecNet also employs a special activation function that preserves the sparsity of the feature maps while effectively encouraging the convergence of the network. The performance of SpecNet is evaluated on three competitive object recognition benchmark tasks (MNIST, CIFAR-10, and SVHN), and compared with four state-of-the-art implementations (LeNet, AlexNet, VGG, and DenseNet). Overall, SpecNet is able to reduce memory consumption by about 60% without significant loss of performance for all tested network architectures.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.10915](http://arxiv.org/abs/1905.10915)

##### PDF
[http://arxiv.org/pdf/1905.10915](http://arxiv.org/pdf/1905.10915)

