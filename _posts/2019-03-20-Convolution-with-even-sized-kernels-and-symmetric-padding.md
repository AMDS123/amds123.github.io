---
layout: post
title: "Convolution with even-sized kernels and symmetric padding"
date: 2019-03-20 08:34:20
categories: arXiv_CV
tags: arXiv_CV CNN Classification Deep_Learning
author: Shuang Wu, Guanrui Wang, Pei Tang, Feng Chen, Luping Shi
mathjax: true
---

* content
{:toc}

##### Abstract
Compact convolutional neural networks gain efficiency mainly through depthwise convolutions, expanded channels and complex topologies, which contrarily aggravate the training efforts. In this work, we identify the shift problem occurs in even-sized kernel (2x2, 4x4) convolutions, and eliminate it by proposing symmetric padding on each side of the feature maps (C2sp, C4sp). Symmetric padding enlarges the receptive fields of even-sized kernels with little computational cost. In classification tasks, C2sp outperforms the conventional 3x3 convolution and obtains comparable accuracies to existing compact convolution blocks, but consumes less memory and time during training. In generation tasks, C2sp and C4sp both achieve improved image qualities and stabilized training. Symmetric padding coupled with even-sized convolution is easy to be implemented into deep learning frameworks, providing promising building units for architecture designs that emphasize training efforts on online and continual learning occasions.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1903.08385](http://arxiv.org/abs/1903.08385)

##### PDF
[http://arxiv.org/pdf/1903.08385](http://arxiv.org/pdf/1903.08385)

