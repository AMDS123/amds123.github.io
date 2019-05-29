---
layout: post
title: "Network Deconvolution"
date: 2019-05-28 16:38:34
categories: arXiv_CV
tags: arXiv_CV CNN Relation
author: Chengxi Ye, Matthew Evanusa, Hua He, Anton Mitrokhin, Thomas Goldstein, James A. Yorke, Cornelia Fermüller, Yiannis Aloimonos
mathjax: true
---

* content
{:toc}

##### Abstract
Convolution is a central operation in Convolutional Neural Networks (CNNs), which applies a kernel or mask to overlapping regions shifted across the image. In this work we show that the underlying kernels are trained with highly correlated data, which leads to co-adaptation of model weights. To address this issue we propose what we call network deconvolution, a procedure that aims to remove pixel-wise and channel-wise correlations before the data is fed into each layer. We show that by removing this correlation we are able to achieve better convergence rates during model training with superior results without the use of batch normalization on the CIFAR-10, CIFAR-100, MNIST, Fashion-MNIST datasets, as well as against reference models from "model zoo" on the ImageNet standard benchmark.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11926](https://arxiv.org/abs/1905.11926)

##### PDF
[https://arxiv.org/pdf/1905.11926](https://arxiv.org/pdf/1905.11926)

