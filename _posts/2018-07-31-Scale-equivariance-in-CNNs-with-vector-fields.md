---
layout: post
title: "Scale equivariance in CNNs with vector fields"
date: 2018-07-31 12:14:45
categories: arXiv_CV
tags: arXiv_CV CNN Classification Relation
author: Diego Marcos, Benjamin Kellenberger, Sylvain Lobry, Devis Tuia
mathjax: true
---

* content
{:toc}

##### Abstract
We study the effect of injecting local scale equivariance into Convolutional Neural Networks. This is done by applying each convolutional filter at multiple scales. The output is a vector field encoding for the maximally activating scale and the scale itself, which is further processed by the following convolutional layers. This allows all the intermediate representations to be locally scale equivariant. We show that this improves the performance of the model by over $20\%$ in the scale equivariant task of regressing the scaling factor applied to randomly scaled MNIST digits. Furthermore, we find it also useful for scale invariant tasks, such as the actual classification of randomly scaled digits. This highlights the usefulness of allowing for a compact representation that can also learn relationships between different local scales by keeping internal scale equivariance.

##### Abstract (translated by Google)
我们研究了将局部尺度等价注入卷积神经网络的效果。这是通过在多个尺度上应用每个卷积滤波器来完成的。输出是用于最大激活标度和标度本身的矢量场编码，其由下面的卷积层进一步处理。这允许所有中间表示在本地尺度上是等同的。我们表明，在回归应用于随机缩放的MNIST数字的缩放因子的比例等效任务中，这可以将模型的性能提高超过$ 20 \％$。此外，我们发现它对尺度不变任务也很有用，例如随机缩放数字的实际分类。这突出了允许紧凑表示的有用性，该表示还可以通过保持内部比例等效来学习不同局部尺度之间的关系。

##### URL
[http://arxiv.org/abs/1807.11783](http://arxiv.org/abs/1807.11783)

##### PDF
[http://arxiv.org/pdf/1807.11783](http://arxiv.org/pdf/1807.11783)

