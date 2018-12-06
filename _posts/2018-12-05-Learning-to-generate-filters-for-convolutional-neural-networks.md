---
layout: post
title: "Learning to generate filters for convolutional neural networks"
date: 2018-12-05 10:16:38
categories: arXiv_CV
tags: arXiv_CV CNN Classification
author: Wei Shen, Rujie Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Conventionally, convolutional neural networks (CNNs) process different images with the same set of filters. However, the variations in images pose a challenge to this fashion. In this paper, we propose to generate sample-specific filters for convolutional layers in the forward pass. Since the filters are generated on-the-fly, the model becomes more flexible and can better fit the training data compared to traditional CNNs. In order to obtain sample-specific features, we extract the intermediate feature maps from an autoencoder. As filters are usually high dimensional, we propose to learn a set of coefficients instead of a set of filters. These coefficients are used to linearly combine the base filters from a filter repository to generate the final filters for a CNN. The proposed method is evaluated on MNIST, MTFL and CIFAR10 datasets. Experiment results demonstrate that the classification accuracy of the baseline model can be improved by using the proposed filter generation method.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01894](http://arxiv.org/abs/1812.01894)

##### PDF
[http://arxiv.org/pdf/1812.01894](http://arxiv.org/pdf/1812.01894)

