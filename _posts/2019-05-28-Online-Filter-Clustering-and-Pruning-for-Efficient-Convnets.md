---
layout: post
title: "Online Filter Clustering and Pruning for Efficient Convnets"
date: 2019-05-28 13:01:39
categories: arXiv_CV
tags: arXiv_CV
author: Zhengguang Zhou, Wengang Zhou, Richang Hong, Houqiang Li
mathjax: true
---

* content
{:toc}

##### Abstract
Pruning filters is an effective method for accelerating deep neural networks (DNNs), but most existing approaches prune filters on a pre-trained network directly which limits in acceleration. Although each filter has its own effect in DNNs, but if two filters are the same with each other, we could prune one safely. In this paper, we add an extra cluster loss term in the loss function which can force filters in each cluster to be similar online. After training, we keep one filter in each cluster and prune others and fine-tune the pruned network to compensate for the loss. Particularly, the clusters in every layer can be defined firstly which is effective for pruning DNNs within residual blocks. Extensive experiments on CIFAR10 and CIFAR100 benchmarks demonstrate the competitive performance of our proposed filter pruning method.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11787](https://arxiv.org/abs/1905.11787)

##### PDF
[https://arxiv.org/pdf/1905.11787](https://arxiv.org/pdf/1905.11787)

