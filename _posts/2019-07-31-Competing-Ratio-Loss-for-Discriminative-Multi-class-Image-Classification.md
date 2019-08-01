---
layout: post
title: "Competing Ratio Loss for Discriminative Multi-class Image Classification"
date: 2019-07-31 07:38:04
categories: arXiv_CV
tags: arXiv_CV Face CNN Image_Classification Classification
author: Ke Zhang, Xinsheng Wang, Yurong Guo, Zhenbing Zhao, Zhanyu Ma, Tony X. Han
mathjax: true
---

* content
{:toc}

##### Abstract
The development of deep convolutional neural network architecture is critical to the improvement of image classification task performance. A lot of studies of image classification based on deep convolutional neural network focus on the network structure to improve the image classification performance. Contrary to these studies, we focus on the loss function. Cross-entropy Loss (CEL) is widely used for training a multi-class classification deep convolutional neural network. While CEL has been successfully implemented in image classification tasks, it only focuses on the posterior probability of correct class when the labels of training images are one-hot. It cannot be discriminated against the classes not belong to correct class (wrong classes) directly. In order to solve the problem of CEL, we propose Competing Ratio Loss (CRL), which calculates the posterior probability ratio between the correct class and competing wrong classes to better discriminate the correct class from competing wrong classes, increasing the difference between the negative log likelihood of the correct class and the negative log likelihood of competing wrong classes, widening the difference between the probability of the correct class and the probabilities of wrong classes. To demonstrate the effectiveness of our loss function, we perform some sets of experiments on different types of image classification datasets, including CIFAR, SVHN, CUB200- 2011, Adience and ImageNet datasets. The experimental results show the effectiveness and robustness of our loss function on different deep convolutional neural network architectures and different image classification tasks, such as fine-grained image classification, hard face age estimation and large-scale image classification.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.13349](http://arxiv.org/abs/1907.13349)

##### PDF
[http://arxiv.org/pdf/1907.13349](http://arxiv.org/pdf/1907.13349)

