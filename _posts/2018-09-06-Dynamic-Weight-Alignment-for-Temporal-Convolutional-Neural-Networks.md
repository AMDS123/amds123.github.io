---
layout: post
title: "Dynamic Weight Alignment for Temporal Convolutional Neural Networks"
date: 2018-09-06 06:50:57
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Brian Kenji Iwana, Seiichi Uchida
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method of improving Convolutional Neural Networks (CNN) by determining the optimal alignment of weights and inputs using dynamic programming. Conventional CNNs convolve learnable shared weights, or filters, across the input data. These filters use an inner product to linearly match the shared weights to a window of the input. However, it is possible that there exists a more optimal alignment of weights. Thus, we propose the use of Dynamic Time Warping (DTW) to dynamically align the weights to optimized input elements. This dynamic alignment is especially useful for time series recognition due to the complexities with temporal distortions, such as varying rates and sequence lengths. We demonstrate the effectiveness of the proposed architecture on the Unipen online handwritten digit and character datasets, the UCI Spoken Arabic Digit dataset, and the UCI Activities of Daily Life dataset.

##### Abstract (translated by Google)
在本文中，我们提出了一种通过使用动态规划确定权重和输入的最佳对齐来改进卷积神经网络（CNN）的方法。传统的CNN在输入数据上卷积可学习的共享权重或过滤器。这些过滤器使用内积将共享权重线性匹配到输入窗口。但是，可能存在更优化的权重对齐。因此，我们建议使用动态时间扭曲（DTW）来动态地将权重对齐到优化的输入元素。由于时间失真的复杂性，例如变化的速率和序列长度，这种动态对准对于时间序列识别特别有用。我们在Unipen在线手写数字和字符数据集，UCI口语阿拉伯数字数据集和UCI日常生活活动数据集上展示了所提架构的有效性。

##### URL
[http://arxiv.org/abs/1712.06530](http://arxiv.org/abs/1712.06530)

##### PDF
[http://arxiv.org/pdf/1712.06530](http://arxiv.org/pdf/1712.06530)

