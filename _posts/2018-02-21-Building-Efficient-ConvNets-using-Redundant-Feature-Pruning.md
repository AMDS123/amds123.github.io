---
layout: post
title: "Building Efficient ConvNets using Redundant Feature Pruning"
date: 2018-02-21 16:31:28
categories: arXiv_CV
tags: arXiv_CV CNN Inference
author: Babajide O. Ayinde, Jacek M. Zurada
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an efficient technique to prune deep and/or wide convolutional neural network models by eliminating redundant features (or filters). Previous studies have shown that over-sized deep neural network models tend to produce a lot of redundant features that are either shifted version of one another or are very similar and show little or no variations; thus resulting in filtering redundancy. We propose to prune these redundant features along with their connecting feature maps according to their differentiation and based on their relative cosine distances in the feature space, thus yielding smaller network size with reduced inference costs and competitive performance. We empirically show on select models and CIFAR-10 dataset that inference costs can be reduced by 40% for VGG-16, 27% for ResNet-56, and 39% for ResNet-110.

##### Abstract (translated by Google)
本文提出了一种通过消除冗余特征（或滤波器）来修剪深度和/或宽卷积神经网络模型的高效技术。以前的研究表明，超大尺寸的深层神经网络模型倾向于产生大量的冗余特征，这些冗余特征既可以是彼此移位的版本，也可以非常相似，并且显示很少或没有变化;从而导致过滤冗余。我们建议根据它们的差异性和基于特征空间中相对余弦距离的修剪来修剪这些冗余特征以及它们的连接特征映射，从而产生更小的网络尺寸，同时降低推理成本和竞争性能。我们根据经验在部分型号和CIFAR-10数据集上显示，VGG-16的推断成本可降低40％，ResNet-56可降低27％，ResNet-110可降低39％。

##### URL
[http://arxiv.org/abs/1802.07653](http://arxiv.org/abs/1802.07653)

##### PDF
[http://arxiv.org/pdf/1802.07653](http://arxiv.org/pdf/1802.07653)

