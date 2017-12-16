---
layout: post
title: "SyncSpecCNN: Synchronized Spectral CNN for 3D Shape Segmentation"
date: 2016-12-02 09:27:34
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Prediction
author: Li Yi, Hao Su, Xingwen Guo, Leonidas Guibas
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we study the problem of semantic annotation on 3D models that are represented as shape graphs. A functional view is taken to represent localized information on graphs, so that annotations such as part segment or keypoint are nothing but 0-1 indicator vertex functions. Compared with images that are 2D grids, shape graphs are irregular and non-isomorphic data structures. To enable the prediction of vertex functions on them by convolutional neural networks, we resort to spectral CNN method that enables weight sharing by parameterizing kernels in the spectral domain spanned by graph laplacian eigenbases. Under this setting, our network, named SyncSpecCNN, strive to overcome two key challenges: how to share coefficients and conduct multi-scale analysis in different parts of the graph for a single shape, and how to share information across related but different shapes that may be represented by very different graphs. Towards these goals, we introduce a spectral parameterization of dilated convolutional kernels and a spectral transformer network. Experimentally we tested our SyncSpecCNN on various tasks, including 3D shape part segmentation and 3D keypoint prediction. State-of-the-art performance has been achieved on all benchmark datasets.

##### Abstract (translated by Google)
在本文中，我们研究了以形状图表示的三维模型的语义标注问题。功能视图用于表示图形上的本地化信息，使得诸如零件段或关键点之类的注释只不过是0-1指示器顶点函数。与2D网格图像相比，形状图是不规则的和非同构的数据结构。为了能够通过卷积神经网络预测它们的顶点函数，我们采用频谱CNN方法，通过在图拉普拉斯特征基所跨越的谱域中参数化核来实现权重共享。在这种背景下，我们的网络名为SyncSpecCNN，努力克服两个关键的挑战：如何共享系数和在图形的不同部分对单一形状进行多尺度分析，以及如何在相关但不同的形状上共享信息由非常不同的图表表示。为了实现这些目标，我们引入了扩展卷积核和谱变换器网络的谱参数化。我们通过实验测试了各种任务的SyncSpecCNN，包括3D形状部分分割和3D关键点预测。在所有基准数据集上都实现了最先进的性能。

##### URL
[https://arxiv.org/abs/1612.00606](https://arxiv.org/abs/1612.00606)

##### PDF
[https://arxiv.org/pdf/1612.00606](https://arxiv.org/pdf/1612.00606)

