---
layout: post
title: "Multi-Sample Dropout for Accelerated Training and Better Generalization"
date: 2019-05-23 17:22:57
categories: arXiv_CV
tags: arXiv_CV Regularization Image_Classification Classification
author: Hiroshi Inoue
mathjax: true
---

* content
{:toc}

##### Abstract
Dropout is a simple but efficient regularization technique for achieving better generalization of deep neural networks (DNNs); hence it is widely used in tasks based on DNNs. During training, dropout randomly discards a portion of the neurons to avoid overfitting. This paper presents an enhanced dropout technique, which we call multi-sample dropout, for both accelerating training and improving generalization over the original dropout. The original dropout creates a randomly selected subset (called a dropout sample) from the input in each training iteration while the multi-sample dropout creates multiple dropout samples. The loss is calculated for each sample, and then the sample losses are averaged to obtain the final loss. This technique can be easily implemented without implementing a new operator by duplicating a part of the network after the dropout layer while sharing the weights among the duplicated fully connected layers. Experimental results showed that multi-sample dropout significantly accelerates training by reducing the number of iterations until convergence for image classification tasks using the ImageNet, CIFAR-10, CIFAR-100, and SVHN datasets. Multi-sample dropout does not significantly increase computation cost per iteration because most of the computation time is consumed in the convolution layers before the dropout layer, which are not duplicated. Experiments also showed that networks trained using multi-sample dropout achieved lower error rates and losses for both the training set and validation set.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.09788](http://arxiv.org/abs/1905.09788)

##### PDF
[http://arxiv.org/pdf/1905.09788](http://arxiv.org/pdf/1905.09788)

