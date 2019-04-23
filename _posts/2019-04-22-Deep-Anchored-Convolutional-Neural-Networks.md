---
layout: post
title: "Deep Anchored Convolutional Neural Networks"
date: 2019-04-22 08:07:00
categories: arXiv_CV
tags: arXiv_CV CNN Prediction
author: Jiahui Huang, Kshitij Dwivedi, Gemma Roig
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have been proven to be extremely successful at solving computer vision tasks. State-of-the-art methods favor such deep network architectures for its accuracy performance, with the cost of having massive number of parameters and high weights redundancy. Previous works have studied how to prune such CNNs weights. In this paper, we go to another extreme and analyze the performance of a network stacked with a single convolution kernel across layers, as well as other weights sharing techniques. We name it Deep Anchored Convolutional Neural Network (DACNN). Sharing the same kernel weights across layers allows to reduce the model size tremendously, more precisely, the network is compressed in memory by a factor of L, where L is the desired depth of the network, disregarding the fully connected layer for prediction. The number of parameters in DACNN barely increases as the network grows deeper, which allows us to build deep DACNNs without any concern about memory costs. We also introduce a partial shared weights network (DACNN-mix) as well as an easy-plug-in module, coined regulators, to boost the performance of our architecture. We validated our idea on 3 datasets: CIFAR-10, CIFAR-100 and SVHN. Our results show that we can save massive amounts of memory with our model, while maintaining a high accuracy performance.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09764](http://arxiv.org/abs/1904.09764)

##### PDF
[http://arxiv.org/pdf/1904.09764](http://arxiv.org/pdf/1904.09764)

