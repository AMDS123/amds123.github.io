---
layout: post
title: "Model Compression by Entropy Penalized Reparameterization"
date: 2019-06-15 22:46:33
categories: arXiv_CV
tags: arXiv_CV Classification
author: Deniz Oktay, Johannes Ball&#xe9;, Saurabh Singh, Abhinav Shrivastava
mathjax: true
---

* content
{:toc}

##### Abstract
We describe an end-to-end neural network weight compression approach that draws inspiration from recent latent-variable data compression methods. The network parameters (weights and biases) are represented in a "latent" space, amounting to a reparameterization. This space is equipped with a learned probability model, which is used to impose an entropy penalty on the parameter representation during training, and to compress the representation using arithmetic coding after training. We are thus maximizing accuracy and model compressibility jointly, in an end-to-end fashion, with the rate--error trade-off specified by a hyperparameter. We evaluate our method by compressing six distinct model architectures on the MNIST, CIFAR-10 and ImageNet classification benchmarks. Our method achieves state-of-the-art compression on VGG-16, LeNet300-100 and several ResNet architectures, and is competitive on LeNet-5.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06624](http://arxiv.org/abs/1906.06624)

##### PDF
[http://arxiv.org/pdf/1906.06624](http://arxiv.org/pdf/1906.06624)

