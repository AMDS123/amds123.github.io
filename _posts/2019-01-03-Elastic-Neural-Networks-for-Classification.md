---
layout: post
title: "Elastic Neural Networks for Classification"
date: 2019-01-03 08:20:48
categories: arXiv_CV
tags: arXiv_CV CNN Classification Prediction
author: Yi Zhou, Yue Bai, Shuvra S. Bhattacharyya, Heikki Huttunen
mathjax: true
---

* content
{:toc}

##### Abstract
In this work we propose a framework for improving the performance of any deep neural network that may suffer from vanishing gradients. To address the vanishing gradient issue, we study a framework, where we insert an intermediate output branch after each layer in the computational graph and use the corresponding prediction loss for feeding the gradient to the early layers. The framework - which we name Elastic network - is tested with several well-known networks on CIFAR10 and CIFAR100 datasets, and the experimental results show that the proposed framework improves the accuracy on both shallow networks (e.g., MobileNet) and deep convolutional neural networks (e.g., DenseNet). We also identify the types of networks where the framework does not improve the performance and discuss the reasons. Finally, as a side product, the computational complexity of the resulting networks can be adjusted in an elastic manner by selecting the output branch according to current computational budget.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.00589](http://arxiv.org/abs/1810.00589)

##### PDF
[http://arxiv.org/pdf/1810.00589](http://arxiv.org/pdf/1810.00589)

