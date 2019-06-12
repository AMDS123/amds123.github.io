---
layout: post
title: "SymNet: Symmetrical Filters in Convolutional Neural Networks"
date: 2019-06-10 19:55:03
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Classification
author: Gregory Dzhezyan, Hubert Cecotti
mathjax: true
---

* content
{:toc}

##### Abstract
Symmetry is present in nature and science. In image processing, kernels for spatial filtering possess some symmetry (e.g. Sobel operators, Gaussian, Laplacian). Convolutional layers in artificial feed-forward neural networks have typically considered the kernel weights without any constraint. In this paper, we propose to investigate the impact of a symmetry constraint in convolutional layers for image classification tasks, taking our inspiration from the processes involved in the primary visual cortex and common image processing techniques. The goal is to assess the extent to which it is possible to enforce symmetrical constraints on the filters throughout the training process of a convolutional neural network (CNN) by modifying the weight update preformed during the backpropagation algorithm and to evaluate the change in performance. The main hypothesis of this paper is that the symmetrical constraint reduces the number of free parameters in the network, and it is able to achieve near identical performance to the modern methodology of training. In particular, we address the following cases: x/y-axis symmetry, point reflection, and anti-point reflection. The performance has been evaluated on four databases of images. The results support the conclusion that while random weights offer more freedom to the model, the symmetry constraint provides a similar level of performance while decreasing substantially the number of free parameters in the model. Such an approach can be valuable in phase-sensitive applications that require a linear phase property throughout the feature extraction process.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.04252](http://arxiv.org/abs/1906.04252)

##### PDF
[http://arxiv.org/pdf/1906.04252](http://arxiv.org/pdf/1906.04252)

