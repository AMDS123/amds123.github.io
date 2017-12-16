---
layout: post
title: "What-and-Where to Match: Deep Spatially Multiplicative Integration Networks for Person Re-identification"
date: 2017-10-14 00:24:20
categories: arXiv_CV
tags: arXiv_CV Re-identification Person_Re-identification CNN Recognition
author: Lin Wu, Yang Wang, Xue Li, Junbin Gao
mathjax: true
---

* content
{:toc}

##### Abstract
Matching pedestrians across disjoint camera views, known as person re-identification (re-id), is a challenging problem that is of importance to visual recognition and surveillance. Most existing methods exploit local regions within spatial manipulation to perform matching in local correspondence. However, they essentially extract \emph{fixed} representations from pre-divided regions for each image and perform matching based on the extracted representation subsequently. For models in this pipeline, local finer patterns that are crucial to distinguish positive pairs from negative ones cannot be captured, and thus making them underperformed. In this paper, we propose a novel deep multiplicative integration gating function, which answers the question of \emph{what-and-where to match} for effective person re-id. To address \emph{what} to match, our deep network emphasizes common local patterns by learning joint representations in a multiplicative way. The network comprises two Convolutional Neural Networks (CNNs) to extract convolutional activations, and generates relevant descriptors for pedestrian matching. This thus, leads to flexible representations for pair-wise images. To address \emph{where} to match, we combat the spatial misalignment by performing spatially recurrent pooling via a four-directional recurrent neural network to impose spatial dependency over all positions with respect to the entire image. The proposed network is designed to be end-to-end trainable to characterize local pairwise feature interactions in a spatially aligned manner. To demonstrate the superiority of our method, extensive experiments are conducted over three benchmark data sets: VIPeR, CUHK03 and Market-1501.

##### Abstract (translated by Google)
在不相交的摄像机视图中匹配行人，被称为人员重新识别（re-id），对于视觉识别和监视来说是一个具有挑战性的问题。大多数现有的方法利用空间操作中的局部区域来执行本地通信中的匹配。然而，它们实质上从每个图像的预分割区域提取\ emph {fixed}表示，并且随后基于所提取的表示来执行匹配。对于这个管道中的模型来说，局部细分的模式对于区分正数和负数是非常重要的，这些模式不能被捕获，从而使它们表现不佳。在本文中，我们提出了一个新的深度乘法积分门控函数，它回答了\ emph {什么和哪里匹配}有效的人员re-id的问题。为了解决\ emph {什么}匹配，我们的深层网络通过以乘法方式学习联合表示来强调常见的局部模式。该网络包括两个卷积神经网络（CNN）来提取卷积激活，并为行人匹配生成相关的描述符。这因此导致成对图像的灵活表示。为了解决\ emph {where}匹配的问题，我们通过经由四向递归神经网络执行空间循环池以对整个图像的所有位置施加空间依赖性来对抗空间不对齐。所提出的网络被设计为端到端可训练的，以空间对齐的方式表征局部成对特征相互作用。为了证明我们的方法的优越性，在三个基准数据集上进行了广泛的实验：VIPeR，CUHK03和Market-1501。

##### URL
[https://arxiv.org/abs/1707.07074](https://arxiv.org/abs/1707.07074)

##### PDF
[https://arxiv.org/pdf/1707.07074](https://arxiv.org/pdf/1707.07074)

