---
layout: post
title: "End-to-end Learning of Cost-Volume Aggregation for Real-time Dense Stereo"
date: 2016-11-17 14:14:02
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Andrey Kuzmin, Dmitry Mikushin, Victor Lempitsky
mathjax: true
---

* content
{:toc}

##### Abstract
We present a new deep learning-based approach for dense stereo matching. Compared to previous works, our approach does not use deep learning of pixel appearance descriptors, employing very fast classical matching scores instead. At the same time, our approach uses a deep convolutional network to predict the local parameters of cost volume aggregation process, which in this paper we implement using differentiable domain transform. By treating such transform as a recurrent neural network, we are able to train our whole system that includes cost volume computation, cost-volume aggregation (smoothing), and winner-takes-all disparity selection end-to-end. The resulting method is highly efficient at test time, while achieving good matching accuracy. On the KITTI 2015 benchmark, it achieves a result of 6.34\% error rate while running at 29 frames per second rate on a modern GPU.

##### Abstract (translated by Google)
我们提出了一个新的深度学习为基础的密集立体匹配方法。与以前的作品相比，我们的方法不使用像素外观描述符的深度学习，而是使用非常快速的经典匹配分数。同时我们的方法使用深度卷积网络来预测成本体积聚集过程的局部参数，本文采用可微域变换来实现。通过把这种变换看作一个循环神经网络，我们能够训练整个系统，其中包括成本体积计算，成本体积聚合（平滑）和赢家通吃差异选择端到端。所得到的方法在测试时间是高效的，同时实现了良好的匹配精度。在KITTI 2015的基准测试中，在现代GPU上以每秒29帧的速度运行，达到了6.34％的错误率。

##### URL
[https://arxiv.org/abs/1611.05689](https://arxiv.org/abs/1611.05689)

##### PDF
[https://arxiv.org/pdf/1611.05689](https://arxiv.org/pdf/1611.05689)

