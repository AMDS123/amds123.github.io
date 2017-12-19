---
layout: post
title: "Dynamic Weight Alignment for Convolutional Neural Networks"
date: 2017-12-18 17:16:07
categories: arXiv_CV
tags: arXiv_CV CNN Relation Recognition
author: Brian Kenji Iwana, Seiichi Uchida
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a method of improving Convolutional Neural Networks (CNN) by determining the optimal alignment of weights and inputs using dynamic programming. Conventional CNNs convolve learnable shared weights, or filters, across the input data. The filters use a linear matching of weights to inputs using an inner product between the filter and a window of the input. However, it is possible that there exists a more optimal alignment of weights. Thus, we propose the use of Dynamic Time Warping (DTW) to dynamically align the weights to optimized input elements. This dynamic alignment is useful for time series recognition due to the complexities of temporal relations and temporal distortions. We demonstrate the effectiveness of the proposed architecture on the Unipen online handwritten digit and character datasets, the UCI Spoken Arabic Digit dataset, and the UCI Activities of Daily Life dataset.

##### Abstract (translated by Google)
在本文中，我们提出了一种改进卷积神经网络（CNN）的方法，通过使用动态规划确定权重和输入的最佳对准。传统CNN在输入数据中卷积可学习的共享权重或过滤器。滤波器使用滤波器和输入窗口之间的内积对输入进行线性匹配。但是，有可能存在更加优化的权重对齐。因此，我们建议使用动态时间规整（Dynamic Time Warping，DTW）来动态调整权重以优化输入元素。由于时间关系和时间扭曲的复杂性，这种动态对齐对于时间序列识别是有用的。我们展示了Unipen在线手写数字和字符数据集，UCI口语阿拉伯数字数据集和UCI日常生活数据集的建议架构的有效性。

##### URL
[http://arxiv.org/abs/1712.06530](http://arxiv.org/abs/1712.06530)

##### PDF
[http://arxiv.org/pdf/1712.06530](http://arxiv.org/pdf/1712.06530)

