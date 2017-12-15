---
layout: post
title: "Depth from a Single Image by Harmonizing Overcomplete Local Network Predictions"
date: 2016-09-07 18:20:19
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Ayan Chakrabarti, Jingyu Shao, Gregory Shakhnarovich
mathjax: true
---

* content
{:toc}

##### Abstract
A single color image can contain many cues informative towards different aspects of local geometric structure. We approach the problem of monocular depth estimation by using a neural network to produce a mid-level representation that summarizes these cues. This network is trained to characterize local scene geometry by predicting, at every image location, depth derivatives of different orders, orientations and scales. However, instead of a single estimate for each derivative, the network outputs probability distributions that allow it to express confidence about some coefficients, and ambiguity about others. Scene depth is then estimated by harmonizing this overcomplete set of network predictions, using a globalization procedure that finds a single consistent depth map that best matches all the local derivative distributions. We demonstrate the efficacy of this approach through evaluation on the NYU v2 depth data set.

##### Abstract (translated by Google)
一个单一的彩色图像可以包含许多提示信息对当地几何结构的不同方面。我们通过使用神经网络来产生一个总结这些线索的中等水平的表示来处理单眼深度估计的问题。该网络被训练成通过在每个图像位置处预测不同顺序，方向和尺度的深度导数来表征局部场景几何特征。然而，网络输出的概率分布不是对每个导数进行单独估计，而是表示对某些系数的置信度，对其他系数是模糊的。然后通过使用全球化程序来协调这个完整的网络预测集合来估计场景深度，所述全球化程序找到与所有局部派生分布最匹配的单个一致的深度图。我们通过纽约大学v2深度数据集评估证明了这种方法的有效性。

##### URL
[https://arxiv.org/abs/1605.07081](https://arxiv.org/abs/1605.07081)

##### PDF
[https://arxiv.org/pdf/1605.07081](https://arxiv.org/pdf/1605.07081)

