---
layout: post
title: "Dense 3D Regression for Hand Pose Estimation"
date: 2017-11-24 14:50:23
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation
author: Chengde Wan, Thomas Probst, Luc Van Gool, Angela Yao
mathjax: true
---

* content
{:toc}

##### Abstract
We present a simple and effective method for 3D hand pose estimation from a single depth frame. As opposed to previous state-of-the-art methods based on holistic 3D regression, our method works on dense pixel-wise estimation. This is achieved by careful design choices in pose parameterization, which leverages both 2D and 3D properties of depth map. Specifically, we decompose the pose parameters into a set of per-pixel estimations, i.e., 2D heat maps, 3D heat maps and unit 3D directional vector fields. The 2D/3D joint heat maps and 3D joint offsets are estimated via multi-task network cascades, which is trained end-to-end. The pixel-wise estimations can be directly translated into a vote casting scheme. A variant of mean shift is then used to aggregate local votes while enforcing consensus between the the estimated 3D pose and the pixel-wise 2D and 3D estimations by design. Our method is efficient and highly accurate. On MSRA and NYU hand dataset, our method outperforms all previous state-of-the-art approaches by a large margin. On the ICVL hand dataset, our method achieves similar accuracy compared to the currently proposed nearly saturated result and outperforms various other proposed methods. Code is available $\href{"this https URL"}{\text{online}}$.

##### Abstract (translated by Google)
我们提出了一个简单而有效的方法来从一个单一的深度帧三维手姿态估计。与先前基于整体3D回归的先进方法相反，我们的方法在密集的像素方式上进行估计。这是通过仔细的姿态参数化设计选择实现的，该选择利用了深度图的二维和三维属性。具体而言，我们将姿态参数分解为一组每个像素的估计，即2D热图，3D热图和单位3D定向矢量场。 2D / 3D联合热图和3D联合偏移通过多任务网络级联进行估计，这是端对端的训练。像素方面的估计可以直接转换成投票方案。然后使用均值漂移的变体来聚合本地投票，同时在估计的三维姿态和通过设计的像素方式的二维和三维估计之间强化共识。我们的方法是高效和高度准确的。在MSRA和纽约大学的手数据集上，我们的方法大大超过了以前所有的最先进的方法。在ICVL手数据集上，我们的方法与目前提出的近饱和结果相比具有相似的精度，并且胜过了其他各种方法。代码可用$ \ href {“this https URL”} {\ text {online}} $。

##### URL
[https://arxiv.org/abs/1711.08996](https://arxiv.org/abs/1711.08996)

##### PDF
[https://arxiv.org/pdf/1711.08996](https://arxiv.org/pdf/1711.08996)

