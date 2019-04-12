---
layout: post
title: "Understanding Individual Neuron Importance Using Information Theory"
date: 2019-04-11 11:35:26
categories: arXiv_CV
tags: arXiv_CV Classification
author: Rana Ali Amjad, Kairen Liu, Bernhard C. Geiger
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we investigate the use of three information-theoretic quantities -- entropy, mutual information with the class variable, and a class selectivity measure based on Kullback-Leibler divergence -- to understand and study the behavior of already trained fully-connected feed-forward neural networks. We analyze the connection between these information-theoretic quantities and classification performance on the test set by cumulatively ablating neurons in networks trained on MNIST, FashionMNIST, and CIFAR-10. Our results parallel those recently published by Morcos et al., indicating that class selectivity is not a good indicator for classification performance. However, looking at individual layers separately, both mutual information and class selectivity are positively correlated with classification performance, at least for networks with ReLU activation functions. We provide explanations for this phenomenon and conclude that it is ill-advised to compare the proposed information-theoretic quantities across layers. Finally, we briefly discuss future prospects of employing information-theoretic quantities for different purposes, including neuron pruning and studying the effect that different regularizers and architectures have on the trained neural network. We also draw connections to the information bottleneck theory of neural networks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1804.06679](http://arxiv.org/abs/1804.06679)

##### PDF
[http://arxiv.org/pdf/1804.06679](http://arxiv.org/pdf/1804.06679)

