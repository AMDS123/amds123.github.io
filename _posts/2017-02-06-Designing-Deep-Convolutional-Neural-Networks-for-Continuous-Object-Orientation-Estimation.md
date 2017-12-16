---
layout: post
title: "Designing Deep Convolutional Neural Networks for Continuous Object Orientation Estimation"
date: 2017-02-06 05:33:45
categories: arXiv_CV
tags: arXiv_CV CNN Prediction Recognition
author: Kota Hara, Raviteja Vemulapalli, Rama Chellappa
mathjax: true
---

* content
{:toc}

##### Abstract
Deep Convolutional Neural Networks (DCNN) have been proven to be effective for various computer vision problems. In this work, we demonstrate its effectiveness on a continuous object orientation estimation task, which requires prediction of 0 to 360 degrees orientation of the objects. We do so by proposing and comparing three continuous orientation prediction approaches designed for the DCNNs. The first two approaches work by representing an orientation as a point on a unit circle and minimizing either L2 loss or angular difference loss. The third method works by first converting the continuous orientation estimation task into a set of discrete orientation estimation tasks and then converting the discrete orientation outputs back to the continuous orientation using a mean-shift algorithm. By evaluating on a vehicle orientation estimation task and a pedestrian orientation estimation task, we demonstrate that the discretization-based approach not only works better than the other two approaches but also achieves state-of-the-art performance. We also demonstrate that finding an appropriate feature representation is critical to achieve a good performance when adapting a DCNN trained for an image recognition task.

##### Abstract (translated by Google)
深度卷积神经网络（DCNN）已被证明是有效的各种计算机视觉问题。在这项工作中，我们证明了其在连续的对象取向估计任务上的有效性，其要求预测对象的0到360度取向。我们通过提出和比较为DCNN设计的三种连续的方向预测方法来做到这一点。前两种方法通过将方向表示为单位圆上的点并使L2损失或角度差损失最小化而起作用。第三种方法首先将连续方位估计任务转换成一组离散方位估计任务，然后使用均值平移算法将离散方位输出转换回连续方位。通过对车辆定位估算任务和行人定位估算任务进行评估，我们证明了基于离散化的方法不仅比其他两种方法效果更好，而且达到了最先进的性能。我们还证明，找到一个适当的特征表示是适应DCNN训练的图像识别任务时获得良好的性能的关键。

##### URL
[https://arxiv.org/abs/1702.01499](https://arxiv.org/abs/1702.01499)

##### PDF
[https://arxiv.org/pdf/1702.01499](https://arxiv.org/pdf/1702.01499)

