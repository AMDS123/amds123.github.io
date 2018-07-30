---
layout: post
title: "Rethinking Spatiotemporal Feature Learning: Speed-Accuracy Trade-offs in Video Classification"
date: 2018-07-27 03:20:56
categories: arXiv_CV
tags: arXiv_CV CNN Image_Classification Represenation_Learning Video_Classification Classification Detection
author: Saining Xie, Chen Sun, Jonathan Huang, Zhuowen Tu, Kevin Murphy
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the steady progress in video analysis led by the adoption of convolutional neural networks (CNNs), the relative improvement has been less drastic as that in 2D static image classification. Three main challenges exist including spatial (image) feature representation, temporal information representation, and model/computation complexity. It was recently shown by Carreira and Zisserman that 3D CNNs, inflated from 2D networks and pretrained on ImageNet, could be a promising way for spatial and temporal representation learning. However, as for model/computation complexity, 3D CNNs are much more expensive than 2D CNNs and prone to overfit. We seek a balance between speed and accuracy by building an effective and efficient video classification system through systematic exploration of critical network design choices. In particular, we show that it is possible to replace many of the 3D convolutions by low-cost 2D convolutions. Rather surprisingly, best result (in both speed and accuracy) is achieved when replacing the 3D convolutions at the bottom of the network, suggesting that temporal representation learning on high-level semantic features is more useful. Our conclusion generalizes to datasets with very different properties. When combined with several other cost-effective designs including separable spatial/temporal convolution and feature gating, our system results in an effective video classification system that that produces very competitive results on several action classification benchmarks (Kinetics, Something-something, UCF101 and HMDB), as well as two action detection (localization) benchmarks (JHMDB and UCF101-24).

##### Abstract (translated by Google)
尽管采用卷积神经网络（CNN）导致视频分析取得了稳步进展，但相对改进并未像2D静态图像分类那样激烈。存在三个主要挑战，包括空间（图像）特征表示，时间信息表示和模型/计算复杂性。 Carreira和Zisserman最近表明，从2D网络中膨胀并在ImageNet上预训练的3D CNN可能是一种有前途的空间和时间表示学习方式。然而，就模型/计算复杂性而言，3D CNN比2D CNN昂贵得多并且易于过度拟合。我们通过系统探索关键网络设计选择，构建有效且高效的视频分类系统，在速度和准确性之间寻求平衡。特别是，我们表明可以通过低成本2D卷积替换许多3D卷积。相当令人惊讶的是，当替换网络底部的3D卷积时，实现了最佳结果（速度和准确性），这表明对高级语义特征的时间表示学习更有用。我们的结论推广到具有非常不同属性的数据集。结合其他几种经济高效的设计，包括可分离的空间/时间卷积和特征门控，我们的系统产生了一个有效的视频分类系统，可以在几个动作分类基准上产生非常有竞争力的结果（Kinetics，Something-something，UCF101和HMDB） ，以及两个动作检测（本地化）基准（JHMDB和UCF101-24）。

##### URL
[http://arxiv.org/abs/1712.04851](http://arxiv.org/abs/1712.04851)

##### PDF
[http://arxiv.org/pdf/1712.04851](http://arxiv.org/pdf/1712.04851)

