---
layout: post
title: "HGC: Hierarchical Group Convolution for Highly Efficient Neural Network"
date: 2019-06-09 15:24:42
categories: arXiv_CV
tags: arXiv_CV CNN
author: Xukai Xie, Yuan Zhou, Sun-Yuan Kung
mathjax: true
---

* content
{:toc}

##### Abstract
Group convolution works well with many deep convolutional neural networks (CNNs) that can effectively compress the model by reducing the number of parameters and computational cost. Using this operation, feature maps of different group cannot communicate, which restricts their representation capability. To address this issue, in this work, we propose a novel operation named Hierarchical Group Convolution (HGC) for creating computationally efficient neural networks. Different from standard group convolution which blocks the inter-group information exchange and induces the severe performance degradation, HGC can hierarchically fuse the feature maps from each group and leverage the inter-group information effectively. Taking advantage of the proposed method, we introduce a family of compact networks called HGCNets. Compared to networks using standard group convolution, HGCNets have a huge improvement in accuracy at the same model size and complexity level. Extensive experimental results on the CIFAR dataset demonstrate that HGCNets obtain significant reduction of parameters and computational cost to achieve comparable performance over the prior CNN architectures designed for mobile devices such as MobileNet and ShuffleNet.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.03657](http://arxiv.org/abs/1906.03657)

##### PDF
[http://arxiv.org/pdf/1906.03657](http://arxiv.org/pdf/1906.03657)

