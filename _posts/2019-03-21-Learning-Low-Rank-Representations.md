---
layout: post
title: "Learning Low-Rank Representations"
date: 2019-03-21 14:56:14
categories: arXiv_AI
tags: arXiv_AI Adversarial CNN Image_Classification Transfer_Learning Classification
author: Amartya Sanyal, Varun Kanade, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
A key feature of neural networks, particularly deep convolutional neural networks, is their ability to "learn" useful representations from data. The very last layer of a neural network is then simply a linear model trained on these "learned" representations. Despite their numerous applications in other tasks such as classification, retrieval, clustering etc., a.k.a. transfer learning, not much work has been published that investigates the structure of these representations or indeed whether structure can be imposed on them during the training process. In this paper, we study the effective dimensionality of the learned representations by models that have proved highly successful for image classification. We focus on ResNet-18, ResNet-50 and VGG-19 and observe that when trained on CIFAR10, CIFAR100 and SVHN, the learned representations exhibit a fairly low rank structure. We propose a modification to the training procedure, which further induces low rank structure on learned activations. Empirically, we show that this has implications for robustness to adversarial examples and compression.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.07090](http://arxiv.org/abs/1804.07090)

##### PDF
[http://arxiv.org/pdf/1804.07090](http://arxiv.org/pdf/1804.07090)

