---
layout: post
title: "SMASH: One-Shot Model Architecture Search through HyperNetworks"
date: 2017-08-17 16:03:33
categories: arXiv_CV
tags: arXiv_CV Knowledge NAS
author: Andrew Brock, Theodore Lim, J.M. Ritchie, Nick Weston
mathjax: true
---

* content
{:toc}

##### Abstract
Designing architectures for deep neural networks requires expert knowledge and substantial computation time. We propose a technique to accelerate architecture selection by learning an auxiliary HyperNet that generates the weights of a main model conditioned on that model's architecture. By comparing the relative validation performance of networks with HyperNet-generated weights, we can effectively search over a wide range of architectures at the cost of a single training run. To facilitate this search, we develop a flexible mechanism based on memory read-writes that allows us to define a wide range of network connectivity patterns, with ResNet, DenseNet, and FractalNet blocks as special cases. We validate our method (SMASH) on CIFAR-10 and CIFAR-100, STL-10, ModelNet10, and Imagenet32x32, achieving competitive performance with similarly-sized hand-designed networks. Our code is available at this https URL

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1708.05344](https://arxiv.org/abs/1708.05344)

##### PDF
[https://arxiv.org/pdf/1708.05344](https://arxiv.org/pdf/1708.05344)

