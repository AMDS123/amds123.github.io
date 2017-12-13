---
layout: post
title: "How to Train a CAT: Learning Canonical Appearance Transformations for Direct Visual Localization Under Illumination Change"
date: 2017-12-12 16:55:21
categories: arXiv_CV
tags: arXiv_CV Face CNN Transfer_Learning
author: Lee Clement, Jonathan Kelly
mathjax: true
---

* content
{:toc}

##### Abstract
Direct visual localization has recently enjoyed a resurgence in popularity with the increasing availability of cheap mobile computing power. The competitive accuracy and robustness of these algorithms compared to state-of-the-art feature-based methods, as well as their natural ability to yield dense maps, makes them an appealing choice for a variety of mobile robotics applications. However, direct methods remain brittle in the face of appearance change due to their underlying assumption of photometric consistency, which is commonly violated in practice. In this paper, we propose to mitigate this problem by training deep convolutional encoder-decoder models to transform images of a scene such that they correspond to a previously-seen canonical appearance. We validate our method in multiple environments and illumination conditions using high-fidelity synthetic RGB-D datasets, and integrate the trained models into a direct visual localization pipeline, yielding improvements in visual odometry (VO) accuracy through time-varying illumination conditions, as well as improved metric relocalization performance under illumination change, where conventional methods normally fail. We further provide a preliminary investigation of transfer learning from synthetic to real environments in a localization context. An open-source implementation of our method using PyTorch is available at https://github.com/utiasSTARS/cat-net.

##### Abstract (translated by Google)
随着便宜移动计算能力的日益普及，直接的视觉本地化近来得到了普及。与最先进的基于特征的方法相比，这些算法的竞争精度和鲁棒性，以及它们自然产生密集地图的能力，使得它们成为各种移动机器人应用的有吸引力的选择。然而，直接的方法在外观变化的情况下仍然是脆弱的，这是由于它们对光度一致性的潜在假设，这在实践中通常被违反。在本文中，我们建议通过训练深卷积编码器 - 解码器模型来转换这个问题，以便转换场景的图像，使得它们对应于先前看到的规范外观。我们使用高保真合成RGB-D数据集在多种环境和照明条件下验证了我们的方法，并将训练好的模型集成到直接的视觉定位流水线中，并通过时变照明条件提高了视觉测距（VO）精度作为光照变化下改进的度量重新定位性能，常规方法通常失败。在本地化的背景下，我们进一步提供了从合成到实际环境的转移学习的初步调查。 https://github.com/utiasSTARS/cat-net上提供了使用PyTorch的方法的开源实现。

##### URL
[http://arxiv.org/abs/1709.03009](http://arxiv.org/abs/1709.03009)

##### PDF
[http://arxiv.org/pdf/1709.03009](http://arxiv.org/pdf/1709.03009)

