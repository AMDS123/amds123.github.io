---
layout: post
title: "Direct Monocular Odometry Using Points and Lines"
date: 2017-03-19 01:59:53
categories: arXiv_CV
tags: arXiv_CV Tracking
author: Shichao Yang, Sebastian Scherer
mathjax: true
---

* content
{:toc}

##### Abstract
Most visual odometry algorithm for a monocular camera focuses on points, either by feature matching, or direct alignment of pixel intensity, while ignoring a common but important geometry entity: edges. In this paper, we propose an odometry algorithm that combines points and edges to benefit from the advantages of both direct and feature based methods. It works better in texture-less environments and is also more robust to lighting changes and fast motion by increasing the convergence basin. We maintain a depth map for the keyframe then in the tracking part, the camera pose is recovered by minimizing both the photometric error and geometric error to the matched edge in a probabilistic framework. In the mapping part, edge is used to speed up and increase stereo matching accuracy. On various public datasets, our algorithm achieves better or comparable performance than state-of-the-art monocular odometry methods. In some challenging texture-less environments, our algorithm reduces the state estimation error over 50%.

##### Abstract (translated by Google)
单眼相机的大多数视觉测距算法通过特征匹配或像素强度的直接对准来聚焦于点，而忽略常见但重要的几何实体：边缘。在本文中，我们提出一种结合点和边的测距算法，以从直接和基于特征的方法的优点中受益。它在无纹理的环境中效果更好，并且通过增加聚合盆地来照明变化和快速运动也更加稳健。我们保留关键帧的深度图，然后在跟踪部分，通过在概率框架中将光度误差和几何误差最小化到匹配边缘来恢复相机姿态。在映射部分，边缘用于加速并提高立体匹配精度。在各种公共数据集上，我们的算法比现有技术的单眼测距法获得更好的或可比的性能。在一些具有挑战性的无纹理环境中，我们的算法将状态估计误差降低了50％以上。

##### URL
[https://arxiv.org/abs/1703.06380](https://arxiv.org/abs/1703.06380)

##### PDF
[https://arxiv.org/pdf/1703.06380](https://arxiv.org/pdf/1703.06380)

