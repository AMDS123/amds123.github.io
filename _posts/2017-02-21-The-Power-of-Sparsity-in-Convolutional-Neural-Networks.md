---
layout: post
title: "The Power of Sparsity in Convolutional Neural Networks"
date: 2017-02-21 04:10:31
categories: arXiv_CV
tags: arXiv_CV Sparse CNN Prediction
author: Soravit Changpinyo, Mark Sandler, Andrey Zhmoginov
mathjax: true
---

* content
{:toc}

##### Abstract
Deep convolutional networks are well-known for their high computational and memory demands. Given limited resources, how does one design a network that balances its size, training time, and prediction accuracy? A surprisingly effective approach to trade accuracy for size and speed is to simply reduce the number of channels in each convolutional layer by a fixed fraction and retrain the network. In many cases this leads to significantly smaller networks with only minimal changes to accuracy. In this paper, we take a step further by empirically examining a strategy for deactivating connections between filters in convolutional layers in a way that allows us to harvest savings both in run-time and memory for many network architectures. More specifically, we generalize 2D convolution to use a channel-wise sparse connection structure and show that this leads to significantly better results than the baseline approach for large networks including VGG and Inception V3.

##### Abstract (translated by Google)
深卷积网络以其高计算和存储需求而闻名。鉴于有限的资源，如何设计一个平衡其规模，培训时间和预测准确性的网络？对于大小和速度的交易准确性来说，一种令人惊讶的有效方法是简单地将每个卷积层中的信道数量减少一个固定的分数，并重新训练网络。在许多情况下，这导致显着更小的网络，精度只有很小的变化。在本文中，我们进一步通过实证检查一种在卷积层中去除滤波器之间的连接的策略，使得我们能够在运行时和内存中为许多网络架构节省成本。更具体地说，我们推广二维卷积来使用通道式稀疏连接结构，并且显示这导致比包括VGG和Inception V3的大型网络的基线方法显着更好的结果。

##### URL
[https://arxiv.org/abs/1702.06257](https://arxiv.org/abs/1702.06257)

##### PDF
[https://arxiv.org/pdf/1702.06257](https://arxiv.org/pdf/1702.06257)

