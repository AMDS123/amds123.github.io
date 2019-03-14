---
layout: post
title: "Multi-Task Zipping via Layer-wise Neuron Sharing"
date: 2019-03-13 09:05:31
categories: arXiv_CV
tags: arXiv_CV
author: Xiaoxi He, Zimu Zhou, Lothar Thiele
mathjax: true
---

* content
{:toc}

##### Abstract
Future mobile devices are anticipated to perceive, understand and react to the world on their own by running multiple correlated deep neural networks on-device. Yet the complexity of these neural networks needs to be trimmed down both within-model and cross-model to fit in mobile storage and memory. Previous studies focus on squeezing the redundancy within a single neural network. In this work, we aim to reduce the redundancy across multiple models. We propose Multi-Task Zipping (MTZ), a framework to automatically merge correlated, pre-trained deep neural networks for cross-model compression. Central in MTZ is a layer-wise neuron sharing and incoming weight updating scheme that induces a minimal change in the error function. MTZ inherits information from each model and demands light retraining to re-boost the accuracy of individual tasks. Evaluations show that MTZ is able to fully merge the hidden layers of two VGG-16 networks with a 3.18% increase in the test error averaged on ImageNet and CelebA, or share 39.61% parameters between the two networks with &lt;0.5% increase in the test errors for both tasks. The number of iterations to retrain the combined network is at least 17.8 times lower than that of training a single VGG-16 network. Moreover, experiments show that MTZ is also able to effectively merge multiple residual networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.09791](http://arxiv.org/abs/1805.09791)

##### PDF
[http://arxiv.org/pdf/1805.09791](http://arxiv.org/pdf/1805.09791)

