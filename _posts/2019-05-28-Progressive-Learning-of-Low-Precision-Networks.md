---
layout: post
title: "Progressive Learning of Low-Precision Networks"
date: 2019-05-28 12:50:01
categories: arXiv_CV
tags: arXiv_CV CNN Inference Deep_Learning
author: Zhengguang Zhou, Wengang Zhou, Xutao Lv, Xuan Huang, Xiaoyu Wang, Houqiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Recent years have witnessed the great advance of deep learning in a variety of vision tasks. Many state-of-the-art deep neural networks suffer from large size and high complexity, which makes it difficult to deploy in resource-limited platforms such as mobile devices. To this end, low-precision neural networks are widely studied which quantize weights or activations into the low-bit format. Though being efficient, low-precision networks are usually hard to train and encounter severe accuracy degradation. In this paper, we propose a new training strategy through expanding low-precision networks during training and removing the expanded parts for network inference. First, we equip each low-precision convolutional layer with an ancillary full-precision convolutional layer based on a low-precision network structure, which could guide the network to good local minima. Second, a decay method is introduced to reduce the output of the added full-precision convolution gradually, which keeps the resulted topology structure the same to the original low-precision one. Experiments on SVHN, CIFAR and ILSVRC-2012 datasets prove that the proposed method can bring faster convergence and higher accuracy for low-precision neural networks.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11781](https://arxiv.org/abs/1905.11781)

##### PDF
[https://arxiv.org/pdf/1905.11781](https://arxiv.org/pdf/1905.11781)

