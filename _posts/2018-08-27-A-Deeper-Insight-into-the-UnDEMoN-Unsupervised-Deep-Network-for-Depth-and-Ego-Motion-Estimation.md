---
layout: post
title: "A Deeper Insight into the UnDEMoN: Unsupervised Deep Network for Depth and Ego-Motion Estimation"
date: 2018-08-27 11:40:58
categories: arXiv_AI
tags: arXiv_AI Pose_Estimation Deep_Learning
author: Madhu Babu V, Anima Majumder, Kaushik Das, Swagat Kumar
mathjax: true
---

* content
{:toc}

##### Abstract
This paper presents an unsupervised deep learning framework called UnDEMoN for estimating dense depth map and 6-DoF camera pose information directly from monocular images. The proposed network is trained using unlabeled monocular stereo image pairs and is shown to provide superior performance in depth and ego-motion estimation compared to the existing state-of-the-art. These improvements are achieved by introducing a new objective function that aims to minimize spatial as well as temporal reconstruction losses simultaneously. These losses are defined using bi-linear sampling kernel and penalized using the Charbonnier penalty function. The objective function, thus created, provides robustness to image gradient noises thereby improving the overall estimation accuracy without resorting to any coarse to fine strategies which are currently prevalent in the literature. Another novelty lies in the fact that we combine a disparity-based depth estimation network with a pose estimation network to obtain absolute scale-aware 6 DOF Camera pose and superior depth map. The effectiveness of the proposed approach is demonstrated through performance comparison with the existing supervised and unsupervised methods on the KITTI driving dataset.

##### Abstract (translated by Google)
本文提出了一种名为UnDEMoN的无监督深度学习框架，用于直接从单眼图像估计密集深度图和6-DoF相机姿态信息。所提出的网络使用未标记的单眼立体图像对进行训练，并且与现有技术相比，显示出在深度和自我运动估计方面提供了优越的性能。通过引入旨在同时最小化空间和时间重建损失的新目标函数来实现这些改进。这些损失使用双线性采样内核定义，并使用Charbonnier惩罚函数进行惩罚。由此创建的目标函数提供了对图像梯度噪声的鲁棒性，从而提高了整体估计精度，而无需采用目前在文献中普遍存在的任何粗略到精细策略。另一个新颖之处在于，我们将基于视差的深度估计网络与姿势估计网络相结合，以获得绝对尺度感知的6 DOF相机姿势和优越的深度图。通过与KITTI驾驶数据集上现有的有监督和无监督方法的性能比较，证明了所提出方法的有效性。

##### URL
[http://arxiv.org/abs/1809.00969](http://arxiv.org/abs/1809.00969)

##### PDF
[http://arxiv.org/pdf/1809.00969](http://arxiv.org/pdf/1809.00969)

