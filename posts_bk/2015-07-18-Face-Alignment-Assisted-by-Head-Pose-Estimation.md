---
layout: post
title: "Face Alignment Assisted by Head Pose Estimation"
date: 2015-07-18 12:36:58
categories: arXiv_CV
tags: arXiv_CV Face Pose_Estimation CNN
author: Heng Yang, Wenxuan Mou, Yichi Zhang, Ioannis Patras, Hatice Gunes, Peter Robinson
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we propose a supervised initialization scheme for cascaded face alignment based on explicit head pose estimation. We first investigate the failure cases of most state of the art face alignment approaches and observe that these failures often share one common global property, i.e. the head pose variation is usually large. Inspired by this, we propose a deep convolutional network model for reliable and accurate head pose estimation. Instead of using a mean face shape, or randomly selected shapes for cascaded face alignment initialisation, we propose two schemes for generating initialisation: the first one relies on projecting a mean 3D face shape (represented by 3D facial landmarks) onto 2D image under the estimated head pose; the second one searches nearest neighbour shapes from the training set according to head pose distance. By doing so, the initialisation gets closer to the actual shape, which enhances the possibility of convergence and in turn improves the face alignment performance. We demonstrate the proposed method on the benchmark 300W dataset and show very competitive performance in both head pose estimation and face alignment.

##### Abstract (translated by Google)
在本文中，我们提出了一种基于显式头部姿态估计的监督级联人脸对齐初始化方案。我们首先研究大多数现有技术的脸部对齐方法的失败情况，并观察这些失败经常具有共同的全局属性，即头部姿势变化通常很大。受此启发，我们提出了一种深度卷积网络模型，用于可靠和准确的头部姿态估计。我们提出了两种用于生成初始化的方案：第一种依赖于在估计下投影平均3D面部形状（由3D面部标志表示）到2D图像上，而不是使用平均面部形状或者随机选择的形状来进行级联面部对准初始化头部姿势第二个根据头部姿态距离从训练集中搜索最近邻形状。通过这样做，初始化接近于实际的形状，这增强了收敛的可能性，并且反过来提高了面对准性能。我们在基准300W数据集上演示所提出的方法，并且在头部姿态估计和脸部对齐中显示非常有竞争力的性能。

##### URL
[https://arxiv.org/abs/1507.03148](https://arxiv.org/abs/1507.03148)

##### PDF
[https://arxiv.org/pdf/1507.03148](https://arxiv.org/pdf/1507.03148)

