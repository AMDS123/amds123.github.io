---
layout: post
title: "Learning Spatial-Aware Regressions for Visual Tracking"
date: 2017-06-22 18:55:35
categories: arXiv_CV
tags: arXiv_CV Tracking CNN
author: Chong Sun, Huchuan Lu, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we analyze the spatial information of deep features, and propose two complementary regressions for robust visual tracking. First, we propose a kernelized ridge regression model wherein the kernel value is defined as the weighted sum of similarity scores of all pairs of patches between two samples. We show that this model can be formulated as a neural network and thus can be efficiently solved. Second, we propose a fully convolutional neural network with spatially regularized kernels, through which the filter kernel corresponding to each output channel is forced to focus on a specific region of the target. Distance transform pooling is further exploited to determine the effectiveness of each output channel of the convolution layer. The outputs from the kernelized ridge regression model and the fully convolutional neural network are combined to obtain the ultimate response. Experimental results on three benchmark datasets validate the effectiveness of the proposed method.

##### Abstract (translated by Google)
在本文中，我们分析了深度特征的空间信息，并提出了两个互补的回归用于稳健的视觉跟踪。首先，我们提出了一个核化岭回归模型，其中核值被定义为两个样本之间所有斑块对的相似度得分的加权和。我们表明，这个模型可以被制定为一个神经网络，从而可以有效地解决。其次，我们提出了一个具有空间正则化核的完全卷积神经网络，通过这个网络，每个输出通道对应的滤波核被迫集中在目标的一个特定区域。距离变换池被进一步利用来确定卷积层的每个输出通道的有效性。将核化岭回归模型和完全卷积神经网络的输出结合起来得到最终响应。三个基准数据集上的实验结果验证了所提出方法的有效性。

##### URL
[https://arxiv.org/abs/1706.07457](https://arxiv.org/abs/1706.07457)

##### PDF
[https://arxiv.org/pdf/1706.07457](https://arxiv.org/pdf/1706.07457)

