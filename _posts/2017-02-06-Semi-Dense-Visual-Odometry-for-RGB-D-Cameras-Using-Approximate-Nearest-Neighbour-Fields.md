---
layout: post
title: "Semi-Dense Visual Odometry for RGB-D Cameras Using Approximate Nearest Neighbour Fields"
date: 2017-02-06 00:12:37
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Yi Zhou, Laurent Kneip, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents a robust and efficient semi-dense visual odometry solution for RGB-D cameras. The core of our method is a 2D-3D ICP pipeline which estimates the pose of the sensor by registering the projection of a 3D semi-dense map of the reference frame with the 2D semi-dense region extracted in the current frame. The processing is speeded up by efficiently implemented approximate nearest neighbour fields under the Euclidean distance criterion, which permits the use of compact Gauss-Newton updates in the optimization. The registration is formulated as a maximum a posterior problem to deal with outliers and sensor noises, and consequently the equivalent weighted least squares problem is solved by iteratively reweighted least squares method. A variety of robust weight functions are tested and the optimum is determined based on the characteristics of the sensor model. Extensive evaluation on publicly available RGB-D datasets shows that the proposed method predominantly outperforms existing state-of-the-art methods.

##### Abstract (translated by Google)
本文为RGB-D摄像机提出了一种稳健而有效的半密集视觉测距解决方案。我们的方法的核心是2D-3D ICP流水线，其通过将参考帧的3D半密集图投影到当前帧中提取的2D半稠密区域来估计传感器的姿态。在欧几里得距离准则下，通过有效实现的近似最近邻域来加速处理，这允许在优化中使用紧凑的高斯 - 牛顿更新。该配准被表述为处理异常值和传感器噪声的最大后验问题，因此通过迭代重新加权最小二乘法来解决等效加权最小二乘问题。测试各种强大的权重函数，并根据传感器模型的特性确定最佳值。对公开可用的RGB-D数据集的广泛评估表明，所提出的方法主要优于现有的最先进的方法。

##### URL
[https://arxiv.org/abs/1702.02512](https://arxiv.org/abs/1702.02512)

##### PDF
[https://arxiv.org/pdf/1702.02512](https://arxiv.org/pdf/1702.02512)

