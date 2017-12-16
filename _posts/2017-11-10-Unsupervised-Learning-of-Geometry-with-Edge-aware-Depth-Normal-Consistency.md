---
layout: post
title: "Unsupervised Learning of Geometry with Edge-aware Depth-Normal Consistency"
date: 2017-11-10 01:39:29
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Prediction
author: Zhenheng Yang, Peng Wang, Wei Xu, Liang Zhao, Ramakant Nevatia
mathjax: true
---

* content
{:toc}

##### Abstract
Learning to reconstruct depths in a single image by watching unlabeled videos via deep convolutional network (DCN) is attracting significant attention in recent years. In this paper, we introduce a surface normal representation for unsupervised depth estimation framework. Our estimated depths are constrained to be compatible with predicted normals, yielding more robust geometry results. Specifically, we formulate an edge-aware depth-normal consistency term, and solve it by constructing a depth-to-normal layer and a normal-to-depth layer inside of the DCN. The depth-to-normal layer takes estimated depths as input, and computes normal directions using cross production based on neighboring pixels. Then given the estimated normals, the normal-to-depth layer outputs a regularized depth map through local planar smoothness. Both layers are computed with awareness of edges inside the image to help address the issue of depth/normal discontinuity and preserve sharp edges. Finally, to train the network, we apply the photometric error and gradient smoothness for both depth and normal predictions. We conducted experiments on both outdoor (KITTI) and indoor (NYUv2) datasets, and show that our algorithm vastly outperforms state of the art, which demonstrates the benefits from our approach.

##### Abstract (translated by Google)
学习通过深度卷积网络（DCN）观看未标记的视频来重建单个图像中的深度近年来引起了显着的关注。在本文中，我们引入了一个无监督深度估计框架的表面法线表示。我们估计的深度被限制为与预测的法线兼容，产生更稳健的几何结果。具体而言，我们制定了边缘感知的深度 - 正常一致性项，并通过在DCN内部构建深度 - 正常层和正常 - 深度层来解决这个问题。深度到正常层将估计的深度作为输入，并且使用基于相邻像素的交叉生产来计算法线方向。然后给定估计的法线，正常深度层通过局部平面光滑性输出正则化的深度图。这两个图层都是在图像内部识别边缘的情况下进行计算的，以帮助解决深度/正常不连续问题并保留尖锐的边缘。最后，为了训练网络，我们将光度误差和梯度平滑应用于深度和正常预测。我们在户外（KITTI）和室内（NYUv2）数据集上进行了实验，结果表明我们的算法大大优于现有技术，这证明了我们的方法带来的好处。

##### URL
[https://arxiv.org/abs/1711.03665](https://arxiv.org/abs/1711.03665)

##### PDF
[https://arxiv.org/pdf/1711.03665](https://arxiv.org/pdf/1711.03665)

