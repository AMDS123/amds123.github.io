---
layout: post
title: "Single-bit-per-weight deep convolutional neural networks without batch-normalization layers for embedded systems"
date: 2019-07-16 09:42:02
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Inference Classification Detection
author: Mark D. McDonnell, Hesham Mostafa, Runchun Wang, Andre van Schaik
mathjax: true
---

* content
{:toc}

##### Abstract
Batch-normalization (BN) layers are thought to be an integrally important layer type in today's state-of-the-art deep convolutional neural networks for computer vision tasks such as classification and detection. However, BN layers introduce complexity and computational overheads that are highly undesirable for training and/or inference on low-power custom hardware implementations of real-time embedded vision systems such as UAVs, robots and Internet of Things (IoT) devices. They are also problematic when batch sizes need to be very small during training, and innovations such as residual connections introduced more recently than BN layers could potentially have lessened their impact. In this paper we aim to quantify the benefits BN layers offer in image classification networks, in comparison with alternative choices. In particular, we study networks that use shifted-ReLU layers instead of BN layers. We found, following experiments with wide residual networks applied to the ImageNet, CIFAR 10 and CIFAR 100 image classification datasets, that BN layers do not consistently offer a significant advantage. We found that the accuracy margin offered by BN layers depends on the data set, the network size, and the bit-depth of weights. We conclude that in situations where BN layers are undesirable due to speed, memory or complexity costs, that using shifted-ReLU layers instead should be considered; we found they can offer advantages in all these areas, and often do not impose a significant accuracy cost.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.06916](http://arxiv.org/abs/1907.06916)

##### PDF
[http://arxiv.org/pdf/1907.06916](http://arxiv.org/pdf/1907.06916)

