---
layout: post
title: "Deep GrabCut for Object Selection"
date: 2017-07-14 18:52:26
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Semantic_Segmentation
author: Ning Xu, Brian Price, Scott Cohen, Jimei Yang, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Most previous bounding-box-based segmentation methods assume the bounding box tightly covers the object of interest. However it is common that a rectangle input could be too large or too small. In this paper, we propose a novel segmentation approach that uses a rectangle as a soft constraint by transforming it into an Euclidean distance map. A convolutional encoder-decoder network is trained end-to-end by concatenating images with these distance maps as inputs and predicting the object masks as outputs. Our approach gets accurate segmentation results given sloppy rectangles while being general for both interactive segmentation and instance segmentation. We show our network extends to curve-based input without retraining. We further apply our network to instance-level semantic segmentation and resolve any overlap using a conditional random field. Experiments on benchmark datasets demonstrate the effectiveness of the proposed approaches.

##### Abstract (translated by Google)
大多数先前的基于边界框的分割方法假设边界框紧密覆盖感兴趣的对象。然而，矩形输入可能太大或太小是很常见的。在本文中，我们提出了一种新的分割方法，使用矩形作为软约束，将其转换为欧氏距离图。卷积编码器 - 解码器网络通过连接这些距离图的图像作为输入并且将对象掩模预测为输出端对端地进行训练。我们的方法得到准确的分割结果给出了粗糙的矩形，同时通用的交互式分割和实例分割。我们展示了我们的网络扩展到基于曲线的输入而无需再培训。我们进一步将我们的网络应用到实例级别的语义分割，并使用条件随机场解决任何重叠。基准数据集的实验证明了所提出方法的有效性。

##### URL
[https://arxiv.org/abs/1707.00243](https://arxiv.org/abs/1707.00243)

##### PDF
[https://arxiv.org/pdf/1707.00243](https://arxiv.org/pdf/1707.00243)

