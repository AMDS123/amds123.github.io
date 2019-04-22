---
layout: post
title: "Feature Fusion for Online Mutual Knowledge Distillation"
date: 2019-04-19 03:18:56
categories: arXiv_CV
tags: arXiv_CV Knowledge Classification
author: Jangho Kim, Minsung Hyun, Inseop Chung, Nojun Kwak
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a learning framework named Feature Fusion Learning (FFL) that efficiently trains a powerful classifier through a fusion module which combines the feature maps generated from parallel neural networks. Specifically, we train a number of parallel neural networks as sub-networks, then we combine the feature maps from each sub-network using a fusion module to create a more meaningful feature map. The fused feature map is passed into the fused classifier for overall classification. Unlike existing feature fusion methods, in our framework, an ensemble of sub-network classifiers transfers its knowledge to the fused classifier and then the fused classifier delivers its knowledge back to each sub-network, mutually teaching one another in an online-knowledge distillation manner. This mutually teaching system not only improves the performance of the fused classifier but also obtains performance gain in each sub-network. Moreover, our model is more beneficial because different types of network can be used for each sub-network. We have performed a variety of experiments on multiple datasets such as CIFAR-10, CIFAR-100 and ImageNet and proved that our method is more effective than other alternative methods in terms of performance of both sub-networks and the fused classifier.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.09058](http://arxiv.org/abs/1904.09058)

##### PDF
[http://arxiv.org/pdf/1904.09058](http://arxiv.org/pdf/1904.09058)

