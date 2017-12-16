---
layout: post
title: "Backpropagation Training for Fisher Vectors within Neural Networks"
date: 2017-02-08 18:19:05
categories: arXiv_CV
tags: arXiv_CV Recognition
author: Patrick Wieschollek, Fabian Groh, Hendrik P.A. Lensch
mathjax: true
---

* content
{:toc}

##### Abstract
Fisher-Vectors (FV) encode higher-order statistics of a set of multiple local descriptors like SIFT features. They already show good performance in combination with shallow learning architectures on visual recognitions tasks. Current methods using FV as a feature descriptor in deep architectures assume that all original input features are static. We propose a framework to jointly learn the representation of original features, FV parameters and parameters of the classifier in the style of traditional neural networks. Our proof of concept implementation improves the performance of FV on the Pascal Voc 2007 challenge in a multi-GPU setting in comparison to a default SVM setting. We demonstrate that FV can be embedded into neural networks at arbitrary positions, allowing end-to-end training with back-propagation.

##### Abstract (translated by Google)
Fisher-Vectors（FV）编码一组多个局部描述符（如SIFT特征）的高阶统计量。他们已经表现出良好的表现与浅层学习架构相结合的视觉识别任务。当前使用FV作为深层架构中的特征描述符的方法假定所有原始输入特征是静态的。我们提出了一个框架，联合学习原始特征，FV参数和分类器参数的传统神经网络风格的表示。与默认的SVM设置相比，我们的概念验证证明可以提高多GPU设置下Pascal Voc 2007挑战的FV性能。我们证明了FV可以嵌入任意位置的神经网络，允许端到端的训练与反向传播。

##### URL
[https://arxiv.org/abs/1702.02549](https://arxiv.org/abs/1702.02549)

##### PDF
[https://arxiv.org/pdf/1702.02549](https://arxiv.org/pdf/1702.02549)

